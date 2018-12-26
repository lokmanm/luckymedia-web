<template>
  <div id="app">
    <navigation/>
    <header-slide/>
    <about-us/>
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import HeaderSlide from "./components/HeaderSlide.vue";
import AboutUs from "./components/AboutUs.vue";
export default {
  name: "app",
  components: {
    Navigation,
    HeaderSlide,
    AboutUs
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Merriweather|Montserrat:700,900");
@import "src/assets/style.scss";
</style>
