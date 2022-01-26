<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
export default {
  name: "App",
  data() {
    return {
      
    }
  },
  components: {
    Header,
    Main,
    Footer,
  },
  methods: {
  
  },
};
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  #app{
    @import "./assets/scss/style.scss";
  }
</style>