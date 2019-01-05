<template>
  <div id="portfolio">
    <div class="gallery-container">
      <h4 class="heading-text" data-aos="fade-up">PORTFOLIO</h4>
      <div class="gallery-grid">
        <div
          v-for="image in images"
          :key="image.id"
          class="cell"
          data-aos="fade-up"
          data-aos-duration="3000"
        >
          <img class="responsive-image" :src="image.url" alt>
        </div>
      </div>
      <h3 class="gallery-sub" data-aos="fade-down" data-aos-duration="3000">
        Check out our
        <a href="https://www.instagram.com/luckymedia.mk" target="_blank">Instagram</a> and
        <a href="https://www.fb.com/LuckyMediaInc" target="_blank">Facebook</a> for more.
      </h3>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: [
        {
          url: require("@/assets/images/SanaProtect.jpg")
        },
        {
          url: require("@/assets/images/Innova.jpg")
        },
        {
          url: require("@/assets/images/Bbc.jpg")
        },
        {
          url: require("@/assets/images/Barber.jpg")
        },
        {
          url: require("@/assets/images/Havana.jpg")
        },
        {
          url: require("@/assets/images/Metal.jpg")
        }
      ]
    };
  },
  methods: {}
};
</script>

<style>
</style>
