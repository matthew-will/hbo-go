<template>
  <div id="app">
    <Landing />
  </div>
</template>

<script>
import Landing from './components/Landing.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    Landing,
    Header
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
