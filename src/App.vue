<template>
  <main id="content">
    <img class="logo" alt="Logo" src="./assets/chiroyce.svg" />
  </main>
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
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
