<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="less">
  // global dependencies
  @import (less) "~node_modules/bootstrap/dist/css/bootstrap.css";
  @import "~assets/less/flat-ui";
  @import "~assets/less/kdvc";
</style>

<script>
export default {
  name: 'App'
}
</script>
