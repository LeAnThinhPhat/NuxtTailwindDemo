<template>
  <div class="home">
    <img alt="Vue logo" src="~assets/provide.png" />
    <h1>WHAT WE DO</h1>
    <h3>
      We consult, build, optimize and run innovative software systems bases on
      customer requirements.
    </h3>
    <img id="we-do" src="~assets/what-we-provide.png" alt="we-provide" />
    <h1>PRODUCT & SERVICE</h1>
    <h3>
      With the latest technology solution, we aim for a prosperous world in the
      future where evryone can connect and get things done essily
    </h3>
    <img id="product" src="~assets/product.png" alt="product" />
    <br />
    <button>See more</button>
  </div>
</template>

<style scoped lang="scss">
/*Smart phone nhỏ*/
@media screen and (min-width: 240px) {
}
/*Iphone(480 x 640)*/
@media screen and (min-width: 320px) {
  @import '~assets/style.scss';
  h1,
  h3 {
    color: #f36f21;
    font-size: 80%;
  }
  .home {
    background-color: black;
    display: inline-block;
    text-align: center;
  }
  #we-do {
    width: 85%;
  }
  #product {
    width: 85%;
  }
  button {
    @include btn_orange();
  }
  button:hover {
    background-color: #f36f21;
    color: white;
    transition: 700ms;
  }
}
/*Tablet nhỏ(480 x 640)*/
@media screen and (min-width: 480px) {
}
/*Ipad dọc(768 x 1024)*/
@media screen and (min-width: 768px) {
  @import '../../assets/style.scss';
  h1,
  h3 {
    color: #f36f21;
    font-size: 100%;
  }
  #we-do {
    width: 65%;
  }
  #product {
    width: 65%;
  }
  button {
    @include btn_orange();
  }
  button:hover {
    background-color: #f36f21;
    color: white;
    transition: 700ms;
  }
}
/*Ipad ngang(1024 x 768)*/
@media screen and (min-width: 1024px) {
}
</style>
