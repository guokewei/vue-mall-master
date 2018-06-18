<template>
  <div id="app">
  <button>abcdedffhd范德萨范德萨i</button>
    <router-view class="main"></router-view>
  </div>
</template>
<script>
  export default {
    name: 'app'
  }
</script>
<style lang="scss" rel="stylesheet/scss">
  @import "assets/style/index.scss";

  #app {
    height: 100%;
  }

  .main {
    background: #ededed;;
  }
</style>
