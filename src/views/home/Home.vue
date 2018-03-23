<template>
  <section id="view_home" class="kdvc-page">

    <kdvc-nav class="kdvc-container" />

  </section>
</template>

<style lang="less">
  @import (reference) "~assets/less/references";

  #view-home {}
</style>

<script>
import KdvcNav from '@/components/Nav/Nav'

export default {
  components: {
    KdvcNav
  },
  mounted () {
    console.log('its alive!')
  }
}
</script>
