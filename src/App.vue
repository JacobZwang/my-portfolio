<template>
  <div id="app">
    <div class="appWrapper">
      <Portfolio />
      <SideBar />
    </div>
  </div>
</template>

<script>
import Portfolio from "./components/Portfolio.vue";
import SideBar from "./components/SideBar.vue";

export default {
  name: "App",
  components: {
    Portfolio,
    SideBar,
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

* {
  margin: 0px;
}

.appWrapper {
  display: flex;
  height: 100vh;
}
</style>
