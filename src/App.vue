<template>
  <div id='app'>
    <!-- <Home/> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import Home from './components/home/Home';

export default {
  name: 'App',
  components: {
    // Home
  }
};
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
