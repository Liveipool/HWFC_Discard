<template>
  <div class="container">
    <head-bar></head-bar>

    <slot></slot>

    <bottom-bar></bottom-bar>
  </div>
</template>

<script>
  import HeadBar from 'components/HeadBar.vue'
  import BottomBar from 'components/BottomBar.vue'

  export default {
    components: {
      HeadBar,
      BottomBar
    }
  }
</script>

<style scoped>
  .container {
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
  }
</style>
