<template>
  <nav>
    <button class="btn-close" :class="{ close: hidden }" @click="triggerSideMenu()"></button>
    <ul id="responsive-menu" :class="{ openmenu: hidden }">
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
      hidden: true
    };
  },

  methods: {
    triggerSideMenu() {
      this.hidden = !this.hidden;
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
nav {
  width: 100%;
  height: 50px;
  position: fixed;
  background-color: black;
}

@media screen and (max-width: 960px) {
  nav {
    display: block !important;
  }
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
  height: 100vh;
  flex-direction: column;
  background: black;
}

li a {
  color: white;
  text-decoration: none;
  text-transform: uppercase;
}

.close {
  display: block;
}

.open {
  display: none;
}

.openmenu {
  display: none;
}

.btn-close {
  background-image: url("../assets/menu.png");
  background-color: black;
  width: 30px;
  height: 30px;
  border: none;
  background-size: cover;
  background-position: center;
  position: absolute;
  z-index: 999;
}
</style>
