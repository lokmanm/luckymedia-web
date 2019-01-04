<template>
  <div>
    <div class="client-container">
      <h4 class="heading-text" data-aos="fade-up">CLIENTS</h4>
      <div class="client-grid" data-aos="fade-up" data-aos-duration="3000">
        <div class="client">
          <dem-lab></dem-lab>
        </div>
        <div class="client">
          <vardar></vardar>
        </div>
        <div class="client">
          <globi></globi>
        </div>
        <div class="client">
          <betonida></betonida>
        </div>
        <div class="client">
          <akva-term></akva-term>
        </div>
        <div class="client">
          <etc></etc>
        </div>
        <div class="client">
          <seeu></seeu>
        </div>
        <div class="client">
          <reka></reka>
        </div>
        <div class="client">
          <culture></culture>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import DemLab from "./../assets/logos/demlab.svg";
import Vardar from "./../assets/logos/vardar.svg";
import Reka from "./../assets/logos/reka.svg";
import Betonida from "./../assets/logos/betonida.svg";
import AkvaTerm from "./../assets/logos/akva.svg";
import Etc from "./../assets/logos/etc.svg";
import Seeu from "./../assets/logos/seeu.svg";
import Globi from "./../assets/logos/globi.svg";
import Culture from "./../assets/logos/culture.svg";

export default {
  components: {
    DemLab,
    Vardar,
    Reka,
    Betonida,
    AkvaTerm,
    Etc,
    Seeu,
    Globi,
    Culture
  }
};
</script>

<style>
</style>
