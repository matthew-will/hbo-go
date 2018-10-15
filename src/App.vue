<template>
  <div id="app">
    <Landing />
  </div>
</template>

<script>
import Landing from './components/Landing.vue'
export default {
  name: 'app',
  components: {
    Landing
  }
}
</script>

<style>
@font-face {
  font-family: 'Gotham-Light';
  src: url('./fonts/Gotham-Light.otf');
}

@font-face {
  font-family: 'Gotham-Medium';
  src: url('./fonts/Gotham-Medium.otf');
}

@font-face {
  font-family: 'Gotham-Bold';
  src: url('./fonts/Gotham-Bold.otf');
}

body {
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  background: black;
}
</style>
