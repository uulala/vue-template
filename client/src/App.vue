<template>
  <div id="app">
    <img src="./assets/logo.png">
    <LeftMenu/>
    <router-view/>
  </div>
</template>

<script>
import LeftMenu from '@/components/LeftMenu'
export default {
  name: 'App',
  components: {
    'LeftMenu': LeftMenu
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
