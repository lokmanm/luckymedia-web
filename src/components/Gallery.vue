<template>
  <div>
    <div class="gallery-container">
      <h4 class="heading-text">PORTFOLIO</h4>
      <div class="gallery-grid">
        <div v-for="image in images" :key="image.id" class="cell">
          <img class="responsive-image" :src="image.url" alt>
        </div>
      </div>
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
