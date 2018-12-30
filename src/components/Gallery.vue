<template>
  <div>
    <div class="gallery-container">
      <h4 class="heading-text">PORTFOLIO</h4>
      <div class="gallery-grid">
        <div v-for="image in images" :key="image.id" class="cell">
          <img width="350px" class="responsive-image" :src="image.url" alt>
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
          url: require("@/assets/lokman-bw.jpg")
        },
        {
          url: require("@/assets/lokman-color.jpg")
        },
        {
          url: require("@/assets/lokman-bw.jpg")
        },
        {
          url: require("@/assets/lokman-color.jpg")
        },
        {
          url: require("@/assets/lokman-bw.jpg")
        },
        {
          url: require("@/assets/lokman-color.jpg")
        },
        {
          url: require("@/assets/lokman-bw.jpg")
        },
        {
          url: require("@/assets/lokman-color.jpg")
        }
      ]
    };
  },
  methods: {}
};
</script>

<style>
</style>
