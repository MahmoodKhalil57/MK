<template>
  <div>
    <div class="row q-pa-xl q-gutter-lg">
      <div class="column">
        <div class="q-pl-sm text-subtitle1 text-grey text-center">
          Data Scientist,<br />
          UIX Web Developer
        </div>
        <div class="row">
          <q-space />
          <q-avatar size="150px">
            <q-img
              loading="eager"
              src="~assets\Untitled.png"
              spinner-color="white"
              alt=""
            />
          </q-avatar>
          <q-space />
        </div>
      </div>
      <div class="column">
        <q-space />
        <q-space />
        <div class="q-pt-xl text-h2 text-white align-center">
          Mahmood Ihab Khalil
        </div>
        <div class="text-grey text-h6 q-ml-lg">Learn it, get it done.</div>
      </div>
    </div>
    <div
      class="q-pt-xl text-center absolute"
      style="transform: translateX(450%) translateY(70px)"
    >
      <q-icon :name="icon" color="primary" size="80px" />
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
  data() {
    return {
      icon: "",
    };
  },
  methods: {
    load_arrow_animation() {
      this.delay(5000).then(() => (this.icon = "expand_less"));
    },
    delay(time) {
      return new Promise((resolve) => setTimeout(resolve, time));
    },
  },
  created: function () {
    this.load_arrow_animation();
  },
};
</script>
