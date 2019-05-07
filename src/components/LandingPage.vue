<template>
  <div id="div-landing-page">
    <div id="div-navbar">
      <span class="g-font-english g-font-size">Jobchain</span>
      <span class="g-font-chinese g-font-size">跨業人才交流計畫</span>
    </div>

    <div id="div-1">
      <div id="div-1-word-1">
        <span class="g-font-chinese">建立我的專業人脈網</span>
      </div>

      <div id="div-1-word-2" class="g-font-size">
        <span class="g-font-chinese">
          發揮所長，讓專業
          <span class="g-font-english">Chain</span>在一起
        </span>
      </div>

      <div>
        <a
          id="top-button"
          class="g-font-chinese"
          href="https://www.surveycake.com/s/BLggD"
          target="_blank"
        >開始交流</a>
      </div>

      <div id="div-svg-1">
        <img src="@/assets/svg/pic_landing_page_1.svg" id="img-svg-1">
      </div>

      <hr class="left-hr">
    </div>

    <div id="div-2">
      <div class="div-left-text-right-svg">
        <div class="div-top-bottom-text">
          <span class="font-subtitle g-font-chinese">每週人才推薦</span>
          <span class="font-subtext g-font-chinese">
            透過
            <span class="g-font-english">Email</span>推薦人才給您做交流，
          </span>
          <span class="font-subtext g-font-chinese">讓您輕鬆建立自己的專業人脈網。</span>
        </div>

        <img src="@/assets/svg/pic_landing_page_2.svg" id="img-svg-2">
      </div>

      <hr class="right-hr">
    </div>

    <div id="div-3">
      <div class="div-left-svg-right-text">
        <div class="div-middle-text">
          <span class="font-subtitle g-font-chinese">與跨業人才合作</span>
          <span class="font-subtext g-font-chinese">透過人才交流，讓您找到能一起進行</span>
          <span class="font-subtext g-font-chinese">專案合作或是經營事業的夥伴。</span>
        </div>

        <img src="@/assets/svg/pic_landing_page_3.svg" id="img-svg-3">
      </div>

      <hr class="left-hr">
    </div>

    <div id="div-4">
      <div class="div-left-text-right-svg">
        <div class="div-top-bottom-text">
          <span class="font-subtitle g-font-chinese">合作成果分享會</span>
          <span class="font-subtext g-font-chinese">透過成果分享會，讓您分享與跨業</span>
          <span class="font-subtext g-font-chinese">人才合作的專案成果。</span>
        </div>

        <img src="@/assets/svg/pic_landing_page_4.svg" id="img-svg-4">
      </div>
    </div>
    <div>
      <div>
        <a
          id="bottom-button"
          class="g-font-chinese"
          href="https://www.surveycake.com/s/BLggD"
          target="_blank"
        >開始交流</a>
      </div>

      <div>
        <a id="arrow-button" href="#div-landing-page">^</a>
      </div>
    </div>

    <div id="div-footer">

      <div id="div-footer-left">
        <div>
          <router-link to="/policy" class="g-font-chinese">/ 隱私政策</router-link>
        </div>

        <div>
          <a class="g-font-chinese" href="mailto:Jobchain2019@gmail.com">/ 聯絡我們</a>
        </div>

        <div id="div-mail">
          <a
            class="g-font-english text-link"
            href="mailto:Jobchain2019@gmail.com"
          >jobchain2019@gmail.com</a>
          <a class="icon-link" href="mailto:Jobchain2019@gmail.com" target="_blank">
            <img id="mail-icon" src="@/assets/svg/btn_footer_icon_mail_normal.svg">
          </a>
        </div>
      </div>

      <div id="div-footer-right">
        <div>
          <a
            class="g-font-chinese"
            href="https://www.facebook.com/groups/jobchain.tw/"
            target="_blank"
          >
            / 加入
            <span class="g-font-english">VIP</span>社團
          </a>
        </div>

        <div id="div-fb">
          <a class="text-link" href="https://www.facebook.com/groups/jobchain.tw/" target="_blank">
            <span class="g-font-english">Jobchain</span>
            <span class="g-font-chinese">跨業人才交流平台 /</span>
          </a>
          <a class="icon-link" href="https://www.facebook.com/groups/jobchain.tw/" target="_blank">
            <img id="fb-icon" src="@/assets/svg/bnt_footer_icon_fbgroup_normal.svg">
          </a>
        </div>
      </div>

    </div>
    
  </div>
</template>

<style scoped src='./LandingPage.css'>
</style>

<style src='./Global.css'>
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
