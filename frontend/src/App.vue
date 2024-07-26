<template>
  <div id="app">
    <Header></Header>
    <h1>Vue with Flask</h1>
    <router-view />
  </div>
</template>

<script>
import Header from './components/TitleHeader.vue';
export default {
  name: 'App',
  components:{
    Header
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
