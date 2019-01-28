<template>
  <nav id="responsive-navbar">
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
}

@media screen and (min-width: 960px) {
  #responsive-navbar {
    display: none;
  }

  button {
    display: none;
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
  background-image: url("../assets/header-bg.png");
  background-size: cover;
  background-attachment: fixed;
  transform: translate3d(0);
  transition: all 0.5s ease-in-out;
}

li a {
  color: white;
  text-decoration: none;
  text-transform: uppercase;
  font-weight: bold;
  font-size: 20px;
}

.close {
  display: block;
}

.open {
  display: none;
}

.openmenu {
  transform: translate3d(0, -100%, 0);
}

.btn-close {
  cursor: pointer;
  background-image: url("../assets/menu.png");
  background-color: black;
  width: 30px;
  height: 30px;
  border: none;
  background-size: cover;
  background-position: center;
  position: absolute;
  z-index: 999;
  right: 10px;
  top: 10px;
}
</style>
