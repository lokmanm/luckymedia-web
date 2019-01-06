<template>
  <div>
    <div class="header">
      <div class="title" data-aos="fade-up" data-aos-duration="3000">
        <span class="element"></span>
      </div>
    </div>
  </div>
</template>

<script>
import Typed from "typed.js";
export default {
  mounted() {
    var options = {
      strings: ["web.", "design.", "branding.", "print.", "social."],
      loop: true,
      showCursor: false,
      smartBackspace: true,
      typeSpeed: 100
    };
    new Typed(".element", options);
  }
};
</script>

<style lang="scss" scoped>
.element {
  font-size: 7.5rem;
  font-weight: 900;
  margin: auto;
  .typed-cursor {
    opacity: 1;
    animation: typedjsBlink 0.7s infinite;
  }
}
@keyframes typedjsBlink {
  50% {
    opacity: 0;
  }
}
</style>
