<template>
  <div id='landing-page'>
    <div id='navbar-block'>
      <span class='text-english g-font-size'>Jobchain </span><span class='text-chinese g-font-size'>跨界人才交流計畫</span>
    </div>

    <div>
      <div>
        <div class='margin_top_word1'>
          <span class='text-english font_size_top1'>建立我的專業人脈網</span>
        </div>
        <div class='margin_top_word2'>
          <p class='text-chinese g-font-size'>
            發揮所長，讓專業<span class='text-english g-font-size'>Chain</span>在一起
          </p>
        </div>
      </div>

      <div>
        <div>
          <a
            id='top_button'
            class='text-chinese'
            href='https://www.surveycake.com/s/BLggD'
            target='_blank'
          >開始交流</a>
        </div>

        <div id='top_svg_1'>
          <img src='@/assets/svg/pic_landing_page_1.svg' />
        </div>

        <hr class='left_hr' />
      </div>
      <div>
        <div class=''>
          <p class='text-chinese'>
            每週人才推薦
          </p>
          <p class='text-chinese'>
            <span class='text-english'>Chain-up</span>將於每週推薦一位跨業人才給您做交流， 讓您輕鬆建立自己的專業人脈網。
          </p>
        </div>

        <div id='top_svg_2'>
          <img src='@/assets/svg/pic_landing_page_2.svg' />
        </div>

        <hr class='right_hr' />
      </div>
    </div>

    <div>
      <div class=''>
        <p class='text-chinese'>
          與跨業人才合作
        </p>
        <p class='text-chinese'>
          <span class='text-english'>Chain-up</span><b>期望透過平台的交流功能，讓您找到能一起完成</b>
          <span class='text-english'>side project</span>或是一起經營事業的合作夥伴。
        </p>
      </div>

      <div id='top_svg_3'>
        <img src='@/assets/svg/pic_landing_page_3.svg' />
      </div>

      <hr class='left_hr' />
    </div>

    <div>
      <div class=''>
        <p class='text-chinese'>
          跨業人才交流會
        </p>
        <p class='text-chinese'>
          <span class='text-english'>Chain-up</span>將於每月舉辦一場小型的人才交流會，您可以在交 流會中分享自己的專業。
        </p>
      </div>

      <div id='top_svg_4'>
        <img src='@/assets/svg/pic_landing_page_4.svg' />
      </div>

      <hr class='right_hr' />
    </div>

    <div>
      <div>
        <a
          id='bottom_button'
          class='text-chinese'
          href='https://www.surveycake.com/s/BLggD'
          target='_blank'
        >開始交流</a>
      </div>

      <div>
        <span>訂閱我們</span>
        <span>每個月收到我們精選的活動成果及最新通知</span>
      </div>

      <div>
        <input type='text'>
      </div>

      <div>
        <a id='arrow_button'>^</a>
      </div>
    </div>

    <div id='footer'>
      <div>
        <router-link
          to='/policy'
          class='text-chinese'
        >/ 隱私政策</router-link>
      </div>

      <div><a
          class='text-chinese'
          href='mailto:Jobchain2019@gmail.com'
        >/ 聯絡我們</a>
      </div>

      <div>
        <a
          class='text-english'
          href='mailto:Jobchain2019@gmail.com'
        >jobchain2019@gmail.com</a>
      </div>

      <img src='@/assets/svg/btn_footer_icon_mail_normal.svg' />
      <div>
        <a
          class='text-chinese'
          href='https://www.facebook.com/groups/jobchain/?ref=bookmarks'
          target='_blank'
        >/ 加入<span class='text-english'>VIP</span>社團</a>
      </div>

      <div>
        <a
          class='text-chinese'
          href='https://www.facebook.com/groups/jobchain/?ref=bookmarks'
          target='_blank'
        ><span class='text-english'>Jobchain</span>跨業人才交流平台 / </a>
      </div>

      <img src='@/assets/svg/bnt_footer_icon_fbgroup_normal.svg' />
    </div>

  </div>
</template>

<style scoped src='./LandingPage.css'>
</style>

<script>
/* eslint-disable */

export default {
  name: "LandingPage",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>
