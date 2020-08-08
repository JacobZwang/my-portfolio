<template>
  <div class="tabletFrame">
    <div class="tabletBezel">
      <iframe
        src="https://splashhacks.io"
        frameborder="0"
        style="background-color: white; border-radius: 5pt; height: 100%; width: 100%; zoom: 0.25;"
      ></iframe>
    </div>
  </div>
</template>
<style scoped>
.tabletFrame {
  margin: 2.5pt;
  background-color: var(--frame);
  /* padding: var(--frameSize); */
  border-radius: var(--frameCorner);
  height: 100vh;
}
.tabletBezel {
  background-color: var(--bezel);
  /* padding: var(--bezelSize); */
  border-radius: var(--bezelCorner);
  height: 100vh;
}
#splashhacks {
  zoom: 0.25;
}
</style>
