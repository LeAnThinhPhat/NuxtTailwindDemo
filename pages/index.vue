/* eslint-disable vue/multi-word-component-names */
// eslint-disable-next-line vue/multi-word-component-names
<template>
  <div class="home">
    <img class="bg" src="../assets/bg.jpg" alt="bg" />
    <img src="../assets/good-job.png" alt="bg-1" />
    <div class="explore">
      <h1>What you'll get from INOTEK?</h1>
      <h3>
        With the latest technology and high-quality human resources, INOTEK
        always strives to bring customers the best quality products and services
        at low prices.
      </h3>
      <router-link to="/contact"><button>Explore</button></router-link>
    </div>
    <img id="service" src="../assets/our-service.png" alt="bg-2" />
  </div>
</template>

<style scoped lang="scss">
@import '../assets/style.scss';
img {
  position: relative;
  width: 100%;
}
.home {
  background-color: black;
  display: inline-block;
  text-align: center;
}
.home .explore {
  background-color: #131313;
  margin: 20px;
  display: inline-block;
  text-align: center;
  width: 30%;
}
h1,
h3 {
  color: white;
  font-size: 100%;
}
button {
  @include btn_orange();
  margin: 25px
}
button:hover {
  background-color: #f36f21;
  color: white;
  transition: 700ms;
}
#service {
  display: inline-block;
  text-align: center;
  width: 70%;
}
/*Smart phone nhỏ*/
// @media screen and (min-width: 240px){

// }
// /*Iphone(480 x 640)*/
// @media screen and (min-width: 320px){
// .explore{
//   width: 90%;
//   background-color: #131313;
//   margin: 20px;
//   display: inline-block;
//   text-align: center;
// }
// h1, h3{
//   color: white;
//   font-size: 80%
// }
// button{
//     @include btn_orange();
//   }
//   button:hover {
//   background-color: #F36F21;
//   color: white;
//   transition: 700ms;
// }
// #service{
//   width: 90%;
// }
// }
// /*Tablet nhỏ(480 x 640)*/
// @media screen and (min-width: 480px){

// }
// /*Ipad dọc(768 x 1024)*/
// @media screen and (min-width: 768px){

// }
// /*Ipad ngang(1024 x 768)*/
// @media screen and (min-width: 1024px){
//   .explore{
//   width: 30%;
//   background-color: #131313;
//   margin: 20px;
//   display: inline-block;
//   text-align: center;
// }
// h1, h3{
//   color: white;
//   font-size: 100%
// }
// button{
//     @include btn_orange();
//   }
//   button:hover {
//   background-color: #F36F21;
//   color: white;
//   transition: 700ms;
// }
// #service{
//   width: 70%;
// }
// }
</style>
