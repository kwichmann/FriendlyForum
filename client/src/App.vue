<template>
  <div id="app">
    <div id="nav">
      <app-nav></app-nav>
    </div>
    <router-view class='container'/>
  </div>
</template>

<script>
import AppNav from '@/components/AppNav.vue';

export default {
  components: {
    AppNav
  },
}
</script>


<style lang="scss">
</style>
