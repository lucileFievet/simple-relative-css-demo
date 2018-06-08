<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>
<!-- @import colors doesn't works from App.scss, but inside tags -->
<style lang="scss" src="./App.scss">
@import './assets/vars/colors.scss'
</style>
