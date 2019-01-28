<template>
  <nav v-on:scroll="onScroll()" id="navbar">
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
  methods: {
    onScroll() {
      let distance = window.pageYOffset;
      let target = 300;

      if (distance > target) {
        document.querySelector("#navbar").style.backgroundColor =
          "rgb(0, 0, 0, 0.8)";
        console.log("bravo");
      } else {
        document.querySelector("#navbar").style.backgroundColor = "transparent";
      }
    }
  },
  created() {
    window.addEventListener("scroll", this.onScroll);
  },
  destroyed() {
    window.removeEventListener("scroll", this.onScroll);
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#navbar {
  width: 100%;
  height: 50px;
  position: fixed;
  transition: all 0.8s ease-in-out;
}

@media screen and (max-width: 960px) {
  nav {
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
}

li a {
  color: white;
  text-decoration: none;
  text-transform: uppercase;
}
</style>
