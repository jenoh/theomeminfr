<template>
  <div class="aligner">
    <div class="container">
      <p class="hello">HELLO !</p>
      <h1>I'M A JUNIOR JAVASCRIPT DEVELOPER</h1>
      <p>The discovery of Arduino in 2017 revealed to me a great passion for programming</p>
      <div class="icons-link">
        <a href="https://twitter.com/codejenoh" target="_blank">
          <img src="../assets/img/twitter.png" alt="twitter_link" />
        </a>
        <a href="https://www.linkedin.com/in/th%C3%A9o-m%C3%A9min-76044a158/" target="_blank">
          <img class="item-right" src="../assets/img/linkedin.png" alt="linkedin_link" />
        </a>
        <a href="https://github.com/jenoh" target="_blank">
          <img src="../assets/img/git.png" alt="git_link" />
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>

<style>
@font-face {
  font-family: "Poppins-Bold";
  src: url("../assets/fonts/Poppins-Bold.ttf");
}
@font-face {
  font-family: "Poppins-Medium";
  src: url("../assets/fonts/Poppins-Medium.ttf");
}
body {
  background-color: #f4f4f4;
}
img {
  margin-top: 5px;
  width: 37px;
}
.icons-link {
  display: flex;
}
.item-right {
  margin-left: 15px;
  margin-right: 15px;
}
p {
  margin: 0;
  font-family: "Poppins-Medium";
  font-size: 35px;
  line-height: 40px;
}
.hello {
  font-family: "Poppins-Bold";
  font-size: 35px;
  /* padding:-20px; */
}
h1 {
  margin: 0;
  font-family: "Poppins-Bold";
  font-size: 48px;
  color: #6740fe;
  line-height: 45px;
}
.aligner {
  display: flex;
  align-items: center;
  justify-content: center;
}
.container {
  /* margin-left: 200px; */
  margin-top: 300px;
  width: 40%;
  display: flex;
  flex-direction: column;
}
@media (max-width: 1250px) {
  .container {
    /* margin-top: 300px; */
    margin-top: 200px;
    width: 90%;
  }
  p {
    font-size: 25px;
  }
}
</style>