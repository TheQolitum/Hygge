<template>
  <div>
    <div class="main__block">
      <navigation />
      <div class="container">
        <div class="main__bg"></div>
        <div class="main__text">Островок датского счастья в сердце Сибири!</div>
      </div>
    </div>
    <div class="apres__ski__block">
      <div class="container">
        <div class="apres__ski__bg"></div>
        <div class="apres__ski__text">HYGGE - уютный apres-ski бар, который расположился в самом центре горнолыжного
        курорта Шерегеш, у подножья горы Зелёная. Наша команда создаёт настоящий уют и комфорт для гостей.</div>
      </div>
    </div>
    <div class="photo__block">
      <div class="container">
        <div class="photo__bg"></div>
        <div class="kitchen__text">HYGGE - уютный apres-ski бар, который расположился в самом центре горнолыжного
          курорта Шерегеш, ная. Наша команда создаёт настоящий уют и комфорт для гостей.</div>
      </div>
    </div>
    <div class="kitchen__block">
      <div class="container">
        <div class="kitchen__bg"></div>
        <div class="kitchen__text">HYGGE - уютный apres-ski бар, который расположился в самом центре горнолыжного
        курорта Шерегеш, у подножья горы Зелёная. Наша команда создаёт настоящий уют и комфорт для гостей.</div>
       </div>
      </div>

    </div>
</template>

<script>

</script>

<style lang="css">
*, *:after, *:before {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  transition: .5s ease-in-out;
}
ul {
  list-style: none;
}
a {
  text-decoration: none;
  outline: none;
}
header:after, .container:after, footer:after, .widget-posts-list li:after {
  content: "";
  display: table;
  clear: both;
}
/*@media (min-width: 767px) {*/
/*  .text__apres-ski{*/
/*    max-width: 500px;*/
/*    max-height: 524px;*/
/*    margin: 50px 40px 0 40px;*/
/*    padding: 40px;*/
/*  }*/
/*}*/
.container {
  margin: 0 auto;
  width: 100%;
  max-width: 1200px;
  padding: 0 15px;
}
.main__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.main__bg{
  background-image: url("assets/main.jpg");
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
}
.main__text{
  position: absolute;
  color: white;
  max-width: 450px;
  max-height: 200px;
  margin: 170px 50px 0 50px;
  font-size: 48px;
  line-height: 70px;
  letter-spacing: 1px;
  /*padding: 40px;*/
  /*background: rgba(0, 0, 0, 0.75);*/
  /*border-radius: 24px;*/
}
.apres__ski__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.apres__ski__bg{
  background-image: url("assets/smorrebrodpear2.JPG");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 100vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
}
.apres__ski__text{
  position: absolute;
  color: white;
  max-width: 500px;
  max-height: 524px;
  margin: 50px 0 50px 0;
  font-size: 24px;
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
}
.photo__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.photo__bg{
  background-image: url("assets/beer.JPG");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 200vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
}
.kitchen__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.kitchen__bg{
  background-image: url("assets/smorrebrodbanan.JPG");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 300vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
}
.kitchen__text{
  position: absolute;
  color: white;
  max-width: 500px;
  max-height: 524px;
  margin: 50px 0 50px 0;
  font-size: 24px;
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
}
</style>
