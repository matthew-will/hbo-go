<template>
    <div id="header">
        <div class="hbo-logo">Logo</div>
        <div class="contact-text">Contact Us</div>
    </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style lang="scss">
#header {
  width: 100vw;
  display: flex;
  justify-content: space-between;
  position: absolute;
  top: 0;
  height: 150px;
  background: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 1) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}
</style>
