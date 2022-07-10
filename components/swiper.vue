<template>

  <div class="swiper-container">
    <div class="swiper-wrapper">
      <div class="swiper-slide">
        <img src="../assets/smorrebrodbanan2.JPG" alt="">
      </div>
      <div class="swiper-slide">
        <img src="../assets/smorrebrodbanan2.JPG" alt="">
      </div>
      <div class="swiper-slide">
        <img src="../assets/smorrebrodbanan.JPG" alt="">
      </div>
    </div>
  </div>

</template>

<script>

import Swiper from 'swiper';
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted: function () {
    var mySwiper = new Swiper('.swiper-container', {
      autoplay: true,
      loop: true
    })
  },
}
</script>

<style lang="css">

</style>
