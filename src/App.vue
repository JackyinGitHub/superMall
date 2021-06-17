<template>
<div id="App">
  <router-view></router-view>
  <main-tabbar></main-tabbar>
</div>

 </template>

<script>
import MainTabbar from 'components/content/mainTabbar'

export default {
  name: "App",
  components: {
    MainTabbar
  }
}
</script>


<style scoped>
  @import "assets/css/base.css";
</style>
