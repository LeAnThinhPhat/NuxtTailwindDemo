/* eslint-disable vue/multi-word-component-names */
// eslint-disable-next-line vue/multi-word-component-names
<template>
  <div class="home">
    <img alt="contact" src="../../assets/contact.png" />
    <h1>
      If you need to know more about technology solutions for outsourcing and
      software system development. Please contact us!
    </h1>
    <h1>Please fill out below form</h1>
    <h2>Thank for visiting</h2>
    <form action="">
      <td>
        <tr>
          <label for="fullName">Full Name </label
          ><br />
        </tr>
        <tr>
          <input type="text" placeholder="Enter your full name" /><br />
        </tr>
        <tr>
          <label for="email">Email </label
          ><br />
        </tr>
        <tr>
          <input type="text" placeholder="Example: name.example.com" /><br />
        </tr>
        <tr>
          <label for="message">Message </label
          ><br />
        </tr>
        <tr>
          <input type="text" placeholder="Enter your requirement" /><br />
        </tr>
        <tr>
          <input type="submit" /><br />
        </tr>
      </td>
    </form>
  </div>
</template>

<style scoped lang="scss">
/*Ipad ngang(1024 x 768)*/
@media screen and (min-width: 1024px) {
  @import '../../assets/style.scss';
  .home {
    background-color: black;
    display: inline-block;
    text-align: center;
  }
  h1 {
    color: #f36f21;
    font-size: 100%;
  }
  h2,
  label {
    color: white;
    padding-left: 0;
    font-size: 100%;
  }
  input[type='text'] {
    width: 50%;
    padding: 10px 90px;
    margin: 10px 5px;
    background-color: #323232;
    color: black;
  }
  input[type='submit'] {
    @include btn_orange();
    background-color: black;
    
  }
  input[type='submit']:hover {
    background-color: #f36f21;
    color: white;
    transition: 700ms;
    
  }
  input:focus {
    background-color: white;
  }
  td {
    // border:1px solid #F36F21;
    width: 20%;
    display: inline-block;
    text-align: center;
  }
}
</style>
