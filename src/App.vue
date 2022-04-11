<template>
  <main id="content">
    <img class="logo" alt="Logo" src="./assets/chiroyce.svg" />
    <div class="bio" or-something>
      <h1>Chiroyce</h1>
      <p>lorem ipsum dolor sit amet</p>
    </div>
  </main>
</template>

<script setup>

</script>

<style scoped>
  img.logo {
    position: absolute;
    top: 50%;
    left: 30%;
    transform: translateY(-50%);
    width: 30vh; /* https://illogicalapple.com/blog/css-vh-bugs */
  }
  div.bio {
    position: absolute;
    top: 50%;
    left: calc(60% + 30vh);
    transform: translateY(-50%);
    width: calc(90% - (60% + 30vh));
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
