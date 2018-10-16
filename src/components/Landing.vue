<template>
  <div>
    <Header />
    <Montage />
  </div>
</template>

<script>
import Header from './Header.vue'
import Montage from './Montage.vue'
export default {
  name: 'Landing',
    components: {
    Header,
    Montage
  }
}
</script>

<style lang="scss">
.top-gradient {
  height: 150px;
  width: 100vw;
  position: absolute;
}
</style>
