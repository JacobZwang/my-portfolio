<template>
  <div class="sideBarWrapper">
    <img
      class="profile"
      src="https://media-exp1.licdn.com/dms/image/C5603AQGP96mu1J-t8g/profile-displayphoto-shrink_400_400/0?e=1602115200&amp;v=beta&amp;t=YZ-aubC-7x9QwDXA26e1-PO9x08yUgYSXhquYfCi1kE"
    />
    <div class="social">
      <img src="~@/assets/email.svg" class="icon" />
      <p2 class="menuText">zwang.jacob@gmail.com</p2>
    </div>
    <div class="social">
      <img
        src="~@/assets/instagram.svg"
        class="icon"
        style="transform: scale(0.8)"
      />
      <p2 class="menuText">@theshortjacob</p2>
    </div>
    <div class="social">
      <img
        src="~@/assets/linkedin.svg"
        class="icon"
        style="transform: scale(0.7) translateY(-3pt)"
      />
      <p2 class="menuText">jacobzwang</p2>
    </div>
    <p3 class="menuText">
      Hi, I'm Jacob Zwang, I'm a web developer, graphic designer, and project
      manager. I can plan, build, and market your production project using the
      newest technology with precision and efficiency.
    </p3>
  </div>
</template>

<style lang="scss" scoped>
.social {
  vertical-align: middle;
  display: inline-block;
  width: 100%;
  text-align: left;
}
.icon {
  width: 40pt;
  display: inline-block;
  margin: auto;
  transition: 400ms;
  vertical-align: middle;
}
.sideBarWrapper {
  background-color: rgb(238, 238, 238);
  height: 100%;
  width: 40pt;
  transition: 400ms ease-out;
  padding: 5pt;
}
.menuText {
  display: none;
  vertical-align: middle;
}
:hover.sideBarWrapper {
  width: 300pt;
  .profile {
    transition: 400ms ease-out;
    border-radius: 10px;
  }
  .menuText {
    display: inline-block;
  }
  .icon {
    width: 20pt;
    height: 20pt;
    object-fit: fill;
    margin: 0px;
    transition: 400ms;
    margin-right: 0.5rem;
  }
}

.profile {
  width: 100%;
  border-radius: 50%;
  transition: 400ms ease-out;
}
</style>
