<template>
  <div>
    <div class="header">
      <div class="title">
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
      strings: ["web. |", "design. |", "branding. |", "print. |", "social. |"],
      loop: true,
      showCursor: false,
      typeSpeed: 50
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
