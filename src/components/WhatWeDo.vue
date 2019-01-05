<template>
  <div id="services">
    <div class="card-container">
      <h4 class="heading-text" data-aos="fade-up">WHAT WE DO</h4>
      <div class="card-grid" data-aos="fade-up" data-aos-duration="2000">
        <div class="card">
          <div class="icon">
            <host></host>
          </div>
          <div class="title">Web Hosting</div>
          <p
            class="description"
          >We provide fast, reliable and secure web hosting solutions for our clients.</p>
          <div class="services">
            <ul>
              <li>Affordable Hosting</li>
              <li>Unlimited Emails</li>
              <li>24/7 Customer Support</li>
              <li>Cpanel Support</li>
            </ul>
          </div>
        </div>
        <div class="card">
          <div class="icon">
            <web></web>
          </div>
          <div class="title">Web Development</div>
          <p
            class="description"
          >Our commitment, creativity and passion is best reflected in this field.</p>
          <div class="services">
            <ul>
              <li>Custom Web Applications</li>
              <li>E-Commerce</li>
              <li>CMS</li>
              <li>Support and Maintenance</li>
            </ul>
          </div>
        </div>
        <div class="card">
          <div class="icon">
            <design></design>
          </div>
          <div class="title">Design & Branding</div>
          <p
            class="description"
          >We promise to make the next big step for your company by providing corporate identity.</p>
          <div class="services">
            <ul>
              <li>Corporate Identity</li>
              <li>UI/UX Design</li>
              <li>Mockup and Concepts</li>
              <li>Social Media Campaigns</li>
            </ul>
          </div>
        </div>
        <div class="card">
          <div class="icon">
            <print></print>
          </div>
          <div class="title">Inhouse Printing</div>
          <p
            class="description"
          >With the best equipment in the industry we offer printing solution of the greatest quality.</p>
          <div class="services">
            <ul>
              <li>Digital Printing</li>
              <li>Large Format Printing</li>
              <li>Apparel Printing</li>
              <li>Affordable Pricing</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Host from "./../assets/services/host.svg";
import Web from "./../assets/services/web.svg";
import Design from "./../assets/services/design.svg";
import Print from "./../assets/services/print.svg";
export default {
  components: {
    Host,
    Web,
    Design,
    Print
  },
  data() {
    return {};
  }
};
</script>

<style>
</style>
