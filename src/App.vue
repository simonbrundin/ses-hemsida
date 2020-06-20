<template>
  <div id="app">
    <AppDownloadBanner />
    <Logo />
    <IntroVideo />
    <SESDescription />
    <StudioPadel />
    <Contact />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
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
    Contact
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
