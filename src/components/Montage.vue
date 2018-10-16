<template>
    <div class="montage">
        <TV />
    </div>
</template>

<script>
import TV from './TV.vue'
export default {
  name: 'Montage',
  components: {
      TV
  }
}
</script>

<style lang="scss">
.montage {
  width: 100vw;
  height: 100vh;
  background-image: url(../assets/montage.jpg);
  background-position: center;
  z-index: 0;
}
</style>
