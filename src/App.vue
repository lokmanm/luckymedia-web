<template>
  <div id="app">
    <navigation/>
    <header-slide/>
    <about-us/>
    <what-we-do/>
    <gallery/>
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import HeaderSlide from "./components/HeaderSlide.vue";
import AboutUs from "./components/AboutUs.vue";
import WhatWeDo from "./components/WhatWeDo.vue";
import Gallery from "./components/Gallery.vue";

export default {
  name: "app",
  components: {
    Navigation,
    HeaderSlide,
    AboutUs,
    WhatWeDo,
    Gallery
  },
  data() {
    return {
      options: {
        scrollOverflow: true,
        navigation: true,
        scrollBar: false
      }
    };
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Merriweather|Montserrat:700,900");
@import "src/assets/style.scss";
</style>
