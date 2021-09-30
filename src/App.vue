<template>
  <div id="app">
    <NavBar />
    <MainSection />
    <Footer />
    <RightsFooter />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import MainSection from "./components/MainSection.vue";
import Footer from "./components/Footer.vue";
import RightsFooter from "./components/RightsFooter.vue";

export default {
  name: "App",
  components: {
    NavBar,
    MainSection,
    Footer,
    RightsFooter,
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
