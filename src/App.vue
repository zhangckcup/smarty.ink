<template>
  <div id="app">
    <el-container>

      <FooterInfo/>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    FooterInfo: () => import('./components/FooterInfo.vue')
  }
}
</script>

<style lang="less">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: relative;
  min-height: 100vh;
}
*{
  margin: 0;
  padding: 0;
}
</style>
