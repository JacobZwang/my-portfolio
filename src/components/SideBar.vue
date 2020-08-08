<template>
  <div class="sideBarWrapper">
    <img
      src="https://media-exp1.licdn.com/dms/image/C5603AQGP96mu1J-t8g/profile-displayphoto-shrink_400_400/0?e=1602115200&amp;v=beta&amp;t=YZ-aubC-7x9QwDXA26e1-PO9x08yUgYSXhquYfCi1kE"
    />
    <p2>
      Hi, I'm Jacob Zwang, I'm a Web Devloper, Graphic Designer, and Project
      Manager. I can plan, build, and market your project.
    </p2>
  </div>
</template>

<style lang="scss" scoped>
.sideBarWrapper {
  background-color: lightgrey;
  height: 100%;
  width: 40pt;
  transition: 300ms ease-out;
  padding: 10px;
}
:hover.sideBarWrapper {
  width: 200pt;
  img {
    border-radius: 10px;
    transition: 300ms ease-out;
  }
}

img {
  width: 100%;
  border-radius: 50%;
  transition: 300ms ease-out;
}
</style>
