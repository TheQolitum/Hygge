<template>
  <div class="photo__block">
    <div class="container">
      <h2>Наши блюда</h2>
      <br>
      <ssr-carousel :slides-per-page='2' loop show-dots :responsive="responsive" :paginate-by-slide="true" peek="1">
        <div class="slide"><img src="~/assets/smorrebrodcucumbersmall.webp" alt="Сморреброд"></div>
        <div class="slide"><img src="~/assets/smorrebrodeggsmall.webp" alt="Сморреброд с яйцом и беконом"></div>
        <div class="slide"><img src="~/assets/smorrebrodpearsmall.webp" alt="Сморреброд с грушей и гарганзолой"></div>
        <div class="slide"><img src="~/assets/smorrebrodroastbeefsmall.webp" alt="Сморреброд с ростбифом"></div>
        <div class="slide"><img src="~/assets/soupsmall.webp" alt="Томатный суп"></div>
      </ssr-carousel>
    </div>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        responsive: [
          {
            maxWidth: 900,
            slidesPerPage: 1
          },
        ]
      }
    }

  }
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
  max-width: 600px;
  min-width: 240px;
}
</style>
