<template>
    <div>
        <div class="tv-outer">
            <img class="tv-container"
                 src="../assets/tv.png"
                 alt="">
            <video autoplay
                   muted
                   src="https://s3.amazonaws.com/weareglow/wp-content/uploads/2018/08/20180040/OpeningVideo_slow.mp4"></video>
        </div>
    </div>
</template>

<script>
export default {
  name: 'TV'
}
</script>

<style lang="scss">
.tv-outer {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
  .tv-container {
    margin-top: 70px;
  }
  video {
    position: absolute;
    width: 763px;
  }
}
</style>
