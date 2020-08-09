<template>
  <div class="portfolioWrapper">
    <div class="infoColumn">
      <div style="margin: 10pt;">
        <slot name="info"></slot>
      </div>
    </div>
    <div class="displayColumn">
      <slot name="display"></slot>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.portfolioWrapper {
  display: flex;
  grid-template-columns: auto;
  grid-template-rows: auto;
  width: 100%;
  height: 100vh;
}
.infoColumn {
  width: 50%;
  height: 100%;
  overflow-y: scroll;
  transition: 400ms;
}
.displayColumn {
  width: 50%;
  height: 100%;
  transition: 400ms;
}
:hover.infoColumn {
  width: 80%;
  transition: 400ms;
  .displayColumn {
    width: 20%;
    transition: 400ms;
  }
}
:hover.displayColumn {
  width: 80%;
  transition: 400ms;
  .infoColumn {
    width: 20%;
    transition: 400ms;
  }
}
</style>
