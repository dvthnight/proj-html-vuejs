<template>
  <div id="app">
    <Header />
    <Main />
    <Footer/>
    
  </div>
</template>

<script>
import Header from "./components/HeaderFitness"
import Main from "./components/MainFitness.vue"
import Footer from "./components/FooterFitness.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/scss/common.scss";
@import "~@fortawesome/fontawesome-free/css/all.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  // margin-top: 60px;
}
</style>
