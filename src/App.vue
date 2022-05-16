<template>
  <div id="app">
    <AppTitle />
    <AppHero />
    <AppGrid />
  </div>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero";
import AppGrid from "./components/AppGrid";

export default {
  name: "App",
  components: {
    AppTitle,
    AppHero,
    AppGrid,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
