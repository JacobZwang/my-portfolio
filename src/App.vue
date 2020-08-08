<template>
  <div id="app">
    <div class="appWrapper">
      <SideBar />
      <Portfolio />
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
  overflow: hidden;
}

:root {
  --frame: lightgrey;
  --frameSize: 1.5pt;
  --bezel: black;
  --bezelSize: 10pt;
  --frameCorner: 10pt;
  --bezelCorner: 10pt;
  --read: #2c3e50;
}

h1 {
  font-size: 30pt;
  text-transform: uppercase;
  margin: 5pt;
  text-align: left;
}
h2 {
  text-align: left;
  text-transform: uppercase;
  margin: 5pt;
}
h3 {
  font-style: italic;
  font-size: 12pt;
  font-weight: normal;
  text-align: left;
  margin: 5pt;
}
p1 {
  text-align: left;
  display: block;
  margin: 5pt;
}
p2 {
  text-align: left;
  display: block;
  font-weight: bold;
}
p3 {
  display: block;
  text-align: left;
  margin: 5pt;
}
</style>
