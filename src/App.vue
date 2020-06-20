<template>
  <div id="app">
    <AppDownloadBanner />
    <Logo />
    <IntroVideo />
    <SESDescription />
    <StudioPadel />
    <Contact />
  </div>
</template>

<script>
import Logo from "./components/Logo.vue";
import AppDownloadBanner from "./components/AppDownloadBanner.vue";
import IntroVideo from "./components/IntroVideo.vue";
import SESDescription from "./components/SESDescription.vue";
import StudioPadel from "./components/StudioPadel.vue";
import Contact from "./components/Contact.vue";

export default {
  name: "App",
  components: {
    Logo,
    AppDownloadBanner,
    IntroVideo,
    SESDescription,
    StudioPadel,
    Contact,
  },
};
</script>

<style>
body {
  margin: 0;
  background: #0f110e;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}
</style>
