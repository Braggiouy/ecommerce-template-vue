<template>
  <div id="app">
    <NavBar />
    <MainSection />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import MainSection from "./components/MainSection.vue";

export default {
  name: "App",
  components: {
    NavBar,
    MainSection,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
