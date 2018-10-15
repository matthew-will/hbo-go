<template>
  <div>
    <Header />
    <div class="montage">
      <img src="../assets/montage.png"
           alt="Background Image">
    </div>
  </div>
</template>

<script>
import Header from './Header.vue'
export default {
  name: 'Landing',
    components: {
    Header
  }
}
</script>

<style lang="scss">
</style>
