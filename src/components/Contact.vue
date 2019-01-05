<template>
  <div id="contact">
    <div class="contact-container">
      <div class="info" data-aos="fade-up" data-aos-duration="3000">
        <h1 class="info-title">say
          <br>
          <span class="info-sub"></span>
        </h1>
        <h4 class="info-heading">DETAILS</h4>
        <div class="info-details">
          <p>Rr. JNA 190, Gostivar 1230
            <br>Republic of Macedonia
            <br>+389 70 50 20 60
            <br>info@luckymedia.mk
            <br>
          </p>
        </div>
      </div>
      <div class="box" data-aos="fade-up" data-aos-duration="3000">
        <h4 class="info-heading">SEND A MESSAGE</h4>
        <form>
          <input type="text" name="name" placeholder="Name">
          <input type="email" name="email" placeholder="Email">
          <textarea name="message" placeholder="Message"></textarea>
          <button type="submit">SEND</button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import Typed from "typed.js";
export default {
  mounted() {
    var options = {
      strings: [
        "hello.",
        "tung.",
        "здраво.",
        "merhaba.",
        "hallo.",
        "ciao.",
        "bonjour."
      ],
      loop: true,
      showCursor: true,
      smartBackspace: true,
      typeSpeed: 100
    };
    new Typed(".info-sub", options);
  }
};
</script>

<style>
</style>
