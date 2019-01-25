<template>
  <header class="star-wars-header"></header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.star-wars-header {
  width: 100%;
  height: 80vh;
  background-image: url("../assets/header.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
</style>
