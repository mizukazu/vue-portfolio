<template>
  <div id="app">
    <!-- <navigation /> -->
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation.vue'
export default {
  components: {
    Navigation
  }
}
</script>

<style lang="scss">
html {
  height: 100%;
  background: #000;
  color: #fff;
  font-family: 'PixelMplus10-Regular';
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.container {
  width: 100%;
  max-width: 960px;
  margin: 0 auto;
  padding: 0 24px;
}
</style>
