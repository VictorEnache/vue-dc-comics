<template>
  <div id="app">
    <Header/>
    <Main/>
  </div>
</template>

<script>
import Header from '@/components/SiteHeader.vue';
import Main from '@/components/site_main.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
*{
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
