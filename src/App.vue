<template>
  <div id="app">
    <MyNewTitle />
    <MyNewBanner />
  </div>
</template>

<script>
import MyNewTitle from "./components/MyNewTitle.vue";
import MyNewBanner from "./components/MyNewBanner.vue";

export default {
  name: "App",
  components: {
    MyNewTitle,
    MyNewBanner
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
