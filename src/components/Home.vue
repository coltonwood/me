<template>
  <div class="welcome">
    <h1>Welcome to coltonwood.com!</h1>
  </div>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.h1 {
  margin: 0;
}
.welcome {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
