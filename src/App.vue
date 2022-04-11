<template>
  <main id="content">
    <div class="stuf">
      <img class="logo" alt="Logo" src="./assets/chiroyce.svg" />
      <div class="bio" or-something>
        <h1>Chiroyce</h1>
        <p>lorem ipsum dolor sit amet</p>
      </div>
    </div>
  </main>
</template>

<script setup>

</script>

<style scoped>
  img.logo {
    width: 30vh; /* https://illogicalapple.com/blog/css-vh-bugs */
    margin-right: 10vw;
  }
  div.bio {
    font-size: 1.4em;
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
