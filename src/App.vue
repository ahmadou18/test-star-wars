<template>
  <div id="app">
    <Navbar/>
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Navbar from "@/components/Navbar";

export default {
  name: "App",
  components: {
    Header,
    Navbar
  }
};
</script>

<style>
html,
body {
  width: 100%;
  height: 100%;
  margin: 0;
}
</style>
