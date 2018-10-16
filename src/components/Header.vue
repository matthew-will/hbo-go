<template>
    <div id="header">
        <div class="hbo-logo">
            <img src="../assets/HBOGO-logo.png"
                 alt="">
        </div>
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
  width: 100%;
  z-index: 1;
  height: 150px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: absolute;
  top: 0;
  background: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 1) 0%,
    rgba(0, 0, 0, 0) 100%
  );
  .hbo-logo {
    margin-left: 50px;
  }
  .contact-text {
    color: white;
    margin-right: 50px;
    font-size: 1.5rem;
    font-family: 'Gotham-Light';
    cursor: pointer;
    transition: color 150ms;
    &:hover {
      color: #0db2ef;
    }
  }
}
</style>
