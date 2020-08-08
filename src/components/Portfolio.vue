<template>
  <div class="portfolioWrapper">
    <div class="infoColumn">
      <div style="margin: 10pt;">
        <h1>Splash Hacks</h1>
        <h3>Splash Hacks is an online Hackathon founded by Ben Swerdlow</h3>
        <h2>Brand Design</h2>
        <p1
          >I named the Hackathon Splash Hacks to emphasize a couple different
          things. The Founder, Ben Swerdlow, wanted to suggest the place of
          origin, Los Angeles, without alienating outsiders. I chose the word
          splash specifically because of it's dual meaning. A splash suggests
          that there is a big impact, with widespread reach. </p1
        ><p1
          >I also created the logo. The word splash is a completely custom
          typeface created just for Splash Hacks and the word hack was a
          carefully chosen font to help maintain brand usability across many
          platforms. </p1
        ><p1>
          Lastly I created the color pallet, style guide, and use cases along
          with Jessica Golden.
        </p1>
        <h2>Web Development</h2>
        <p1>
          I led the web development team in creating the Splash Hacks website in
          Vue JS. My team was infemailar with Vue, however I believed it was the
          best option so quickly got my team up to speed and had them developing
          in no time. To further speed up production, we used agile development,
          meaning we pushed small improvements frequently rather than waiting
          for large perfected updates.
        </p1>
        <p1>
          While most hackathon websites are all the same, I designed the Splash
          Hacks website to stand out and attract users. However, most
          importantly, it does not compromise on usability. It's concise,
          beautiful, and feels as though it is itself alive.
        </p1>
        <h2>Marketing</h2>
        <p1>
          After the website and branding was complete, I created marketing
          material to help promote the hackathon and spread awareness. I was
          able to cleverly incorporate the logo in many places.
        </p1>
      </div>
    </div>
    <Demo class="displayColumn" />
  </div>
</template>

<script>
import Demo from "@/components/Demo.vue";

export default {
  components: {
    Demo,
  },
};
</script>

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
