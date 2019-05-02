<template>
  <div id="landing-page">
    <div id="navbar-block">
      <span class="text-english g-font-size">Jobchain</span>
      <span class="text-chinese g-font-size">跨業人才交流計畫</span>
    </div>

    <div>
      <div class="margin_top_word1">
        <span class="text-chinese font_size_top1">建立我的專業人脈網</span>
      </div>
      <div class="margin_top_word2">
        <p class="text-chinese g-font-size">
          發揮所長，讓專業
          <span class="text-english g-font-size">Chain</span>在一起
        </p>
      </div>
    </div>

    <div>
      <div>
        <a
          id="top_button"
          class="text-chinese"
          href="https://www.surveycake.com/s/BLggD"
          target="_blank"
        >開始交流</a>
      </div>

      <div id="top_svg_1">
        <img src="@/assets/svg/pic_landing_page_1.svg" class="svg_big">
        <img src="@/assets/svg/pic_landing_page_1_small.svg" class="svg_small">
      </div>

      <hr class="left_hr">
    </div>

    <div class="block">
      <div class="text-block">
        <span class="subtitle text-chinese">每週人才推薦</span>
        <span class="subtext text-chinese">
          透過
          <span class="text-english">Email</span>推薦人才給您做交流，讓您輕鬆建立自己的專業人脈網。
        </span>
      </div>

      <div id="top_svg_2">
        <img src="@/assets/svg/pic_landing_page_2.svg" class="svg_big">
        <img src="@/assets/svg/pic_landing_page_2_small.svg" class="svg_small">
      </div>
    </div>

    <hr class="right_hr">

    <div class="block-reverse">
      <div class="text-block">
        <span class="subtitle text-chinese">與跨業人才合作</span>
        <span class="subtext text-chinese">透過人才交流，讓您找到能一起進行專案合作或是經營事業的夥伴。</span>
      </div>

      <div id="top_svg_3">
        <img src="@/assets/svg/pic_landing_page_3.svg" class="svg_big">
        <img src="@/assets/svg/pic_landing_page_3_small.svg" class="svg_small">
      </div>
    </div>

    <hr class="left_hr">

    <div class="block">
      <div class="text-block">
        <span class="subtitle text-chinese">合作成果分享會</span>
        <span class="subtext text-chinese">透過成果分享會，讓您分享與跨業人才合作的專案成果。</span>
      </div>

      <div id="top_svg_4">
        <img src="@/assets/svg/pic_landing_page_4.svg" class="svg_big">
        <img src="@/assets/svg/pic_landing_page_4_small.svg" class="svg_small">
      </div>
    </div>

    <hr class="right_hr">

    <div>
      <div>
        <a
          id="bottom_button"
          class="text-chinese"
          href="https://www.surveycake.com/s/BLggD"
          target="_blank"
        >開始交流</a>
      </div>

      <div>
        <a id="arrow_button" href="#landing-page">^</a>
      </div>
    </div>

    <div id="footer-block">
      <div id="footer-left-block">
        <div>
          <router-link to="/policy" class="text-chinese">/ 隱私政策</router-link>
        </div>

        <div>
          <a class="text-chinese" href="mailto:Jobchain2019@gmail.com">/ 聯絡我們</a>
        </div>

        <div id="footer-left-mail">
          <a class="text-english" href="mailto:Jobchain2019@gmail.com">jobchain2019@gmail.com</a>
          <a class="mail-link" href="mailto:Jobchain2019@gmail.com" target="_blank">
            <img id="mail-icon" src="@/assets/svg/btn_footer_icon_mail_normal.svg">
          </a>
        </div>
      </div>

      <div id="footer-right-block">
        <div>
          <a
            class="text-chinese"
            href="https://www.facebook.com/groups/jobchain.tw/"
            target="_blank"
          >
            / 加入
            <span class="text-english">VIP</span>社團
          </a>
        </div>

        <div id="footer-right-fb">
          <div>
            <a
              class="text-chinese"
              href="https://www.facebook.com/groups/jobchain.tw/"
              target="_blank"
            >
              <span class="text-english">Jobchain</span>跨業人才交流平台 /
            </a>
          </div>
          <a class="fb-link" href="https://www.facebook.com/groups/jobchain.tw/" target="_blank">
            <img id="fb-icon" src="@/assets/svg/bnt_footer_icon_fbgroup_normal.svg">
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped src='./LandingPage.css' lang='scss'>
</style>

<script src='https://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js'>
/* eslint-disable */
$("#arrow-button").on("click", function() {
  var target = $(this.getAttribute("href"));

  $("body").animate(
    {
      scrollTop: target.offset().top
    },
    2000
  );
});
$(function() {
  $("body")
    .hide()
    .show();
});
</script>

<script>
/* eslint-disable */
export default {
  name: "LandingPage",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  head: {
    meta: [{ name: "viewport", content: "width=device-width,initial-scale=1" }]
  }
};
</script>
