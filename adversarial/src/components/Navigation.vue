<template>
  <div class="banner">
    <div class="headers title">Adversarial Education</div>
    <div class="headers page-title">-</div>
    <div class="headers page-title">{{ pageTitle }}</div>
    <div class="links">
      <a href="#" class="nav">Home</a>
      <a href="#" class="nav">FAQ</a>
      <a href="#" class="nav">Demo</a>
      <a href="#" class="nav">API</a>
      <a href="#" class="nav">GitHub</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navigation',
  props: {
    pageTitle: String
  }
}
</script>

<style>
.banner {
  display: flex;
  width: 100%;
  height: 5em;
  background-color: #D3DAE4;
}

.headers {
  display: inline-block;
  color: #333333;
  font-weight: bolder;
  font-family: "Raleway-italic";
  font-size: 28pt;
  margin-top: .5em;
}

.title {
  margin-left: 1em;
}

.page-title {
  margin-left: .5em;
  margin-top: .5em;
}

.title {
  margin-left: 1em;
}

.page-title {
  margin-left: 10px;
}

.links {
  margin-left: auto;
  margin-top: 2em;
}

a.nav {
  color: #333333;
  font-family: "Montserrat";
  text-decoration: none;
  margin-right: 35px;
  display: inline-block; 
}

a.nav:hover {
  color: #0C68BE;
}

a.nav:active {
  font-weight: bold;
}

@media (max-width: 940px) {
  .headers {
    font-size: 12pt;
  }

  /* .links {

  } */

  /* a {

  } */
}
</style>

