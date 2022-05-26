<template>
  <q-page>
    <div class="parallax_wrapper">
      <div class="parallax_group intro_screen" id="intro">
        <section-one></section-one>
      </div>
      <div class="space"></div>
      <div class="parallax_group" id="group-1">
        <section-two></section-two>
      </div>
      <div class="space"></div>
      <div class="parallax_group" id="group-2">
        <section-three></section-three>
      </div>
      <div class="space"></div>
      <div class="parallax_group" id="group-3">
        <section-four></section-four>
      </div>
      <div class="space"></div>
      <div class="parallax_group outro_screen" id="outro">
        <section-five></section-five>
      </div>
    </div>
  </q-page>
</template>

<script>
import SectionOne from "src/components/SectionOne.vue";
import SectionTwo from "src/components/SectionTwo.vue";
import SectionThree from "src/components/SectionThree.vue";
import SectionFour from "src/components/SectionFour.vue";
import SectionFive from "src/components/SectionFive.vue";

export default {
  components: {
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
  },
};
</script>
