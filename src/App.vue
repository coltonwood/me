<template>
  <div class="h-full">
    <Home />
  </div>
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
@import "./assets/styles/styles.css";
</style>
