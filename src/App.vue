<template>
  <div id="app">
    <Fix/>
    <Header />
    <Main />
    <Footer/>
    
  </div>
</template>

<script>
import Header from "./components/HeaderFitness"
import Main from "./components/MainFitness.vue"
import Footer from "./components/FooterFitness.vue"
import Fix from "./components/FixFitness.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    Fix
  }
}
</script>

<style lang="scss">
@import "./assets/scss/common.scss";
@import "~@fortawesome/fontawesome-free/css/all.css";

#app {
  font-family: "Barlow Semi Condensed", sans-serif, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  // margin-top: 60px;
}
</style>
