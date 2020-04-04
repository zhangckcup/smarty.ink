<template>
  <div id="app">
    <main-navbar></main-navbar>
    <router-view></router-view>
    <footer-info></footer-info>
  </div>
</template>

<script>
export default {
  components: {
    MainNavbar: () => import("@/components/MainNavbar.vue"),
    FooterInfo: () => import("@/components/FooterInfo.vue")
  }
}
</script>

<style lang="less">
  
</style>
