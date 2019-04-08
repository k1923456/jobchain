<template>
  <div>
    <div class='navbar'>
      <span class='engtext font_size_nav'>Jobchain </span><span class='chitext font_size_nav'>跨界人才交流計畫</span>
    </div>
    <div>
      <div class='margin_top_word1'>
        <span class='engtext font_size_top1'>建立我的專業人脈網<span>
      </div>
      <div class='margin_top_word2'>
        <span class='chitext font_size_nav'>發揮所長，讓專業<span><span class='engtext font_size_nav'>Chain</span><span class='chitext font_size_nav'>在一起</span>
      </div>
      <div>
        <span class='top_button chitext font_size_top_button color_top_button'>開始交流</span>
      </div>
      <div class='div_top_svg_1'>
        <img src='@/assets/svg/pic_landing_page_1.svg'>
      </div>
    </div>
    <div>
      <div class='div_top_svg_2'>
        <img src='@/assets/svg/pic_landing_page_2.svg'>
      </div>
    </div>
    <div>
      <div class='div_top_svg_3'>
        <img src='@/assets/svg/pic_landing_page_3.svg'>
      </div>
    </div>
    <div>
      <div class='div_top_svg_4'>
        <img src='@/assets/svg/pic_landing_page_4.svg'>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add 'scoped' attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.navbar {
  background-color: #efad3b;
  margin-bottom: 137px;
  text-align: center;
}
.engtext {
  font-family: 'Times New Roman', Times, serif;
  color: #5b4016;
}
.chitext {
  font-family: 'DFKai-sb';
  color: #5b4016;
}
.font_size_nav {
  font-size: 40px;
}
.font_size_top1 {
  font-size: 60px;
}
.font_size_top_button {
  font-size: 30px;
}
.top_button {
  width: 227px;
  height: 65.4px;
  padding: 11.7px 42px 11.7px 42px;
  border-radius: 43px;
  background-color: #efad3b;
  text-align: center;
}
.div_top_svg_1 {
  width: 490.8px;
  height: 490.8px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  object-fit: contain;
}
.div_top_svg_2 {
  width: 512px;
  height: 512px;
  float: right;
  object-fit: contain;
}
.div_top_svg_3 {
  width: 512px;
  height: 404px;
  float: left;
  object-fit: contain;
}
.div_top_svg_4 {
  width: 512px;
  height: 512px;
  float: right;
  object-fit: contain;
}
.margin_top_word1 {
  margin-bottom: 34px;
}
.margin_top_word2 {
  margin-bottom: 54.6px;
}
.color_top_button {
  color: #ffffff;
}
</style>
