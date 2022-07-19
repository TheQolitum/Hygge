<template>
<div>
  <div class="main__block">
    <div class="main__bg"></div>
      <div class="container">
        <navigation />
        <p class="main__text">Островок датского счастья в сердце Сибири!</p>
      </div>
  </div>
    <div class="apres__ski__block">
      <div class="apres__ski__bg"></div>
        <div class="container">
        <p class="apres__ski__text">HYGGE - уютный apres-ski бар, который расположился в самом центре горнолыжного
        курорта Шерегеш, у подножья горы Зелёная. Наша команда создаёт настоящий уют и комфорт для гостей.</p>
      </div>
    </div>
  <div class="kitchen__block">
    <div class="kitchen__bg"></div>
      <div class="container">
        <p class="kitchen__text">HYGGE объединяет лучшие блюда датской и европейской кухни.</p>
        <p class="sub-kitchen__text">В меню предствлены классические датские сморреброды, а так
        же авторские блюда от нашего шефа.</p>
      </div>
    </div>
  <photo />
  <div class="beer__block">
    <div class="beer__bg"></div>
    <div class="container">
      <p class="beer__text"> Для нашего бара, мы привозим
      необычные сорта крафтового пива и сидра.</p>
    </div>
  </div>
  <div class="footer">
    <div class="container">
      <br>
      <div class="info">
        <div class="column">
          <p style="font-weight: 600">Ежедневно с 09:00 до 19:00</p>
        </div>
        <div class="column">
          <p style="font-weight: 600">Контактные данные</p>
          <p>+7-911-025-79-68</p>
          <p>gesh.hygge@gmail.com</p>
        </div>
      </div>
      <br>
      <p class="ip">2018−22 © ИП Писенко Е.В. ИНН: 000 000 000 000 ОГРН: 000 000 000 000 000</p>
    </div>
    <br>
    <div class="footer__img"></div>
    <br>
  </div>
</div>
</template>

<script>

</script>

<style lang="css">
@font-face {
  font-family: Montserrat-Regular;
  src: url("/fonts/Montserrat-Regular/fonts/Montserrat-Regular.ttf");
  src: url("/fonts/Montserrat-Regular/fonts/Montserrat-Regular.eot");
  src: url("/fonts/Montserrat-Regular/fonts/Montserrat-Regular.woff");
  src: url("/fonts/Montserrat-Regular/fonts/Montserrat-Regular.svg");
}
*, *:after, *:before {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  /*transition: .5s ease-in-out;*/
  font-family: Montserrat-Regular;
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
.container {
  margin: 0 auto;
  width: 100%;
  max-width: 1200px;
  /*padding: 0 15px;*/
  height: 100%;
  position: relative;
}
.main__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.main__bg{
  background-image: url("assets/around.webp");
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
  background-attachment: fixed;
}
.main__text{
  position: absolute;
  color: white;
  max-width: 500px;
  margin: 170px 50px 0 0;
  font-size: clamp(24px, 5vw, 40px);
  line-height: 70px;
  letter-spacing: 1px;
  padding: 40px;
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
  background-color: green;

  background-image: url("assets/smorrebrodpear2.webp");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 100vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
  background-attachment: fixed;
}
.apres__ski__text{
  position: absolute;
  color: white;
  max-width: 500px;
  /*max-height: 524px;*/
  margin: 50px;
  font-size: clamp(1rem, 0.7857rem + 0.9524vw, 1.5rem);
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
  bottom: 100px;
}
.kitchen__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.kitchen__bg{
  background-color: green;
  background-image: url("assets/main.webp");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 300vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
  background-attachment: fixed;
}
.kitchen__text{
  position: absolute;
  color: white;
  max-width: 515px;
  /*max-height: 524px;*/
  margin: 50px;
  font-size: clamp(1rem, 0.7857rem + 0.9524vw, 1.5rem);
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
}
.sub-kitchen__text{
  position: absolute;
  color: white;
  max-width: 515px;
  /*max-height: 524px;*/
  margin: 50px;
  font-size: clamp(1rem, 0.7857rem + 0.9524vw, 1.5rem);
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
  right: 0;
  bottom: 0;
}
.beer__block{
  position: relative;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.beer__bg{
  background-color: green;
  background-image: url("assets/beer.webp");
  position: absolute;
  width: 100%;
  height: 100%;
  /*top: 300vh;*/
  left: 0;
  background-position: center;
  background-size: cover;
  z-index: -5;
  background-attachment: fixed;
}
.beer__text{
  position: absolute;
  color: white;
  max-width: 515px;
  /*max-height: 524px;*/
  margin: 50px;
  font-size: clamp(1rem, 0.7857rem + 0.9524vw, 1.5rem);
  line-height: 30px;
  letter-spacing: 1px;
  padding: 40px;
  background: rgba(0, 0, 0, 0.75);
  border-radius: 24px;
  right: 150px;
  bottom: 150px;
}
.footer{
  background-color: black;
  color: white;
  font-size: clamp(1rem, 0.7857rem + 0.9524vw, 1.5rem);
}
.info{
  display: flex;
  align-items: center;
  /*justify-content: center;*/
}
.column{
  flex: 1 0 50%;
}
.ip{
  font-size: 12px;
}
.footer__img{
  background-image: url("assets/footer.png");
  height: 180px;
  width: 100%;
  background-repeat: repeat-x;
  background-size: 310px;
}
@media (max-width: 767px) {
.main__text{
  line-height: 40px;
  margin: 0;
  left: 0;
}
.apres__ski__text, .kitchen__text, .beer__text{
  line-height: 25px;
  margin: 50px;
  left: 0;
}
.beer__text{
  bottom: 0;
  right: 0;
}
.info{
  padding: 10px;
}
.ip{
  padding: 10px;
}
}
@media (max-height: 800px) {
.main__text{
  bottom: 0;
}
.apres__ski__text{
 bottom: 0;
}
.kitchen__text{
  padding: 24px;
}
.sub-kitchen__text{
  padding: 24px;
}
.info{
  padding: 10px;
}
.ip{
  padding: 10px;
}
}
</style>
