<template>
  <div class="welcome">
    <p>coltonwood.com</p>
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
p {
  margin: 0;
  color: white;
  font-size: 2rem;
  font-weight: 500;
}
.welcome {
  display: flex;
  height: 100%;
  justify-content: center;
  align-items: center;
}
</style>
