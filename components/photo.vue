<template>
  <div class="photo__block">
    <div class="container">
      <ssr-carousel  :slides-per-page='2' loop show-dots show-arrows>
        <div class="slide"><img src="~/assets/smorrebrodbanan22.webp" alt="df"></div>
        <div class="slide"><img src="~/assets/smorrebrodcucumber22.webp" alt="df"></div>
        <div class="slide"><img src="~/assets/smorrebrodegg22.webp" alt="df"></div>
        <div class="slide"><img src="~/assets/smorrebrodfish22.webp" alt="df"></div>
        <div class="slide"><img src="~/assets/smorrebrodroastbeef22.webp" alt="df"></div>
        <div class="slide"><img src="~/assets/soup2.webp" alt="df"></div>
      </ssr-carousel>
      <img src="assets/beer2.webp" alt="df">
    </div>
  </div>
</template>

<script>

</script>

<style lang="css">
.photo__block{
  position: relative;
  height: 60vh;
  padding: 5vh;
}
.slide{
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  overflow: hidden;
  height: 40vh;
}
img{
  max-width: 100%;
  min-width: 240px;
}
</style>
