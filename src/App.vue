<template>
  <main id="content">
    <img class="logo" alt="Logo" src="./assets/chiroyce.svg" />
  </main>
</template>

<script setup>

</script>

<style scoped>
  img.logo {
    position: absolute;
    top: 50%;
    left: 30vw;
    transform: translateY(-50%);
    height: 50vh; /* https://illogicalapple.com/blog/css-vh-bugs */
  }
</style>
<style>
  main#content {
    width: 100vw;
    height: 100vh;
    position: absolute;
    top: 0px;
    left: 0px;
  }
</style>
