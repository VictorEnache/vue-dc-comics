<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Main />
    <Prefooter />
    <Footer />
    <Postfooter />
  </div>
</template>

<script>
import Header from "@/components/SiteHeader.vue";
import Main from "@/components/site_main.vue";
import Prefooter from "@/components/site_prefooter.vue";
import Footer from "@/components/site_footer.vue";
import Postfooter from "@/components/site_postfooter.vue";
import Jumbotron from "@/components/hero_image.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Prefooter,
    Footer,
    Postfooter,
    Jumbotron
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  /*   -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
