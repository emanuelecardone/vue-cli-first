<template>
  <div id="app">
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: black;
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  
}
</style>
