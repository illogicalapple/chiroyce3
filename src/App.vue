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
    float: left;
  }
  div.bio {
    font-size: 1.4em;
    display: inline-block;
    top: 50%;
    position: absolute;
    transform: translateY(-50%);
  }
  div.stuf {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 100vw;
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
