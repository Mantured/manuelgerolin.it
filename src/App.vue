<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Navbar from "./components/Navbar.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Navbar />
  <Main />
  <Footer />
</template>

<style lang="scss">
@import "./assets/scss/main.scss";
#app {
  font-family: "Red Hat Display", sans-serif;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100vh; //something push down, watch m / fixed with reset
}
</style>
