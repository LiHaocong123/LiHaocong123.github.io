<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>


// import QA from './components/QA.vue';
import TextPage from './views/TextPage.vue';
export default {
  name: 'App',
  components: {
    TextPage
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
