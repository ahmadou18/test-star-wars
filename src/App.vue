<template>
  <div id="app">
    <responsiveMenu/>
    <Navbar/>
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Navbar from "@/components/Navbar";
import responsiveMenu from "@/components/responsiveMenu";

export default {
  name: "App",
  components: {
    Header,
    Navbar,
    responsiveMenu
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Open+Sans");

html,
body {
  width: 100%;
  height: 100%;
  margin: 0;
}

* {
  font-family: "Open Sans", sans-serif;
}

/* @media screen and (max-width: 960px) {
  responsiveMenu {
    display: block;
  }
}
@media screen and (max-width: 961px) {
  responsiveMenu {
    display: none;
  }

  Navbar {
    display: block;
  }
} */
</style>
