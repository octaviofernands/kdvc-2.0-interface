<template>
  <nav class="kdvc-nav">
    <kdvc-logo class="kdvc-nav__logo"/>
    <ul class="kdvc-nav__menu">
      <li class="kdvc-nav__menu-item">
        <router-link to="/">item 1</router-link>
      </li>
      <li class="kdvc-nav__menu-item">
        <router-link to="/">item 2</router-link>
      </li>
      <li class="kdvc-nav__menu-item">
        <router-link to="/">item 3</router-link>
      </li>
    </ul>
  </nav>
</template>

<style lang="less">
  @import (reference) "~assets/less/references";

  .kdvc-nav {
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    width: 100%;
    &__logo {
      font-size: 40px;
    }
    &__menu {}
    &__menu-item {}
  }
</style>

<script>
import KdvcLogo from '@/components/Logo/Logo'
export default {
  components: {
    KdvcLogo
  }
}
</script>
