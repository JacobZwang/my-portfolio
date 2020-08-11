<template>
  <div id="app">
    <div class="appWrapper">
      <SideBar />
      <!-- <div class="portfolio" style="overflow-y: scroll; width: 100%">
      <div style="height: 100vh;"></div>-->
      <router-view></router-view>
      <!-- </div> -->
    </div>
  </div>
</template>

<script>
import SideBar from "./components/SideBar.vue";

export default {
  name: "App",
  components: {
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
.portfolio {
  overflow-y: scroll;
  /* Hide scrollbar for IE, Edge and Firefox */
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}
/* Hide scrollbar for Chrome, Safari and Opera */
.portfolio::-webkit-scrollbar {
  display: none;
}
</style>
