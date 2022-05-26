<template>
  <div class="parallax_layer base_layer">
    <div class="parallax_layer mid_layer q-gutter-xl">
      <q-space />
      <q-space />
      <q-space />
      <q-card height="150px" class="my-card text-center .shadow-24">
        <q-img
          position="0% 0%"
          style="filter: brightness(60%)"
          src="~assets/section_five/image.png"
          alt=""
          spinner-color="white"
        />

        <q-card-section
          class="text-black text-subtitle1"
          style="max-width: 300px"
        >
          I have always been facinated by data science and the possibilities it
          opened up. I mainly focus on machine learning, ai, and deep learning,
          looking forward to tackling natural language processing soon!
        </q-card-section>
      </q-card>
      <q-space />
    </div>

    <span class="invisible"> Base Layer page </span>
  </div>
  <div class="parallax_layer bot_layer"></div>
  <div class="parallax_layer mid_layer q-gutter-xl">
    <q-space />
    <div class="text-h1 text-white">Who is MK</div>
    <q-space />
    <q-space />
    <q-space />
  </div>
  <div class="parallax_layer top_layer">
    <div
      style="
        position: absolute;
        background-color: white;
        width: 400px;
        height: 20px;
        transform: translateX(-250px) translateY(60px);
        border-radius: 0px 0px 50px 50px;
        opacity: 0.7;
      "
    ></div>
    <div
      style="
        position: absolute;
        background-color: gray;
        width: 300px;
        height: 20px;
        transform: translateX(-250px) translateY(100px);
        border-radius: 0px 0px 50px 50px;
        opacity: 0.7;
      "
    ></div>
    <div
      style="
        position: absolute;
        background-color: gray;
        width: 175px;
        height: 20px;
        transform: translateX(310px) translateY(-300px);
        border-radius: 50px 50px 0px 0px;
        opacity: 0.7;
      "
    ></div>
    <div
      style="
        position: absolute;
        background-color: white;
        width: 250px;
        height: 20px;
        transform: translateX(310px) translateY(-260px);
        border-radius: 50px 50px 0px 0px;
        opacity: 0.7;
      "
    ></div>
    <div
      style="
        position: absolute;
        background-color: white;
        width: 300px;
        height: 20px;
        transform: translateX(310px) translateY(260px);
        border-radius: 3px 3px 12px 12px;
        opacity: 0.7;
      "
    ></div>
    <span class="invisible">Top Layer Page</span>
  </div>
  <div class="parallax_layer final_layer"></div>
</template>

<script>
export default {
  name: "SectionFive",
  setup() {
    return {};
  },
};
</script>
