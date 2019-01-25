<template>
  <nav>
    <ul>
      <li>
        <router-link to="/">le coté lumineux</router-link>
      </li>
      <li>
        <router-link to="/">le coté obscur</router-link>
      </li>
      <li>
        <router-link to="/">l'empire</router-link>
      </li>
      <li>
        <router-link to="/">les droides</router-link>
      </li>
      <li>
        <router-link to="/">les ewoks</router-link>
      </li>
      <li>
        <router-link to="/">jabba le hutt</router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
nav {
  width: 100%;
  height: 50px;
  position: fixed;
}

ul {
  width: 100%;
  height: 50px;
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

li a {
  color: white;
  text-decoration: none;
  text-transform: uppercase;
}
</style>
