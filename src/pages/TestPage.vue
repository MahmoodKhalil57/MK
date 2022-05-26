
<template>
  <div class="container">
    <div class="q-pa-md text-white text-h6 fixed-top-left">MK</div>
    <section>
      <div class="fit window-height column items-center">
        <q-space />
        <div class="row q-gutter-lg">
          <div class="column">
            <div class="q-pl-sm text-subtitle1 text-grey text-left">
              Computer Scientist
            </div>
            <q-avatar size="150px">
              <img src="~assets\Untitled.png" />
            </q-avatar>
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

        <q-space />
      </div>
    </section>
    <section class="q-gutter-xl">
      <q-parallax>
        <template v-slot:content="scope">
          <div
            class="q-gutter-xl absolute row justify-center items-center"
            :style="{
              top: scope.percentScrolled * 70 - 10 + '%',
              left: 0,
              right: 0,
            }"
          >
            <div class="text-h1 text-white">Data Science</div>
            <q-card class="my-card text-center .shadow-24">
              <q-img
                src="~assets\data_science.jpg"
                alt=""
                spinner-color="white"
                style="height: 140px; max-width: 300px"
              />

              <q-card-section style="max-width: 300px">
                I have always been facinated by data science and the
                possibilities it opened up. I mainly focus on machine learning,
                ai, and deep learning, looking forward to tackling natural
                language processing soon!
              </q-card-section>
            </q-card>
          </div>
        </template>
      </q-parallax>
    </section>
    <section class="q-gutter-xl">
      <q-parallax>
        <template v-slot:content="scope">
          <div
            class="q-gutter-xl absolute row justify-center items-center"
            :style="{
              top: scope.percentScrolled * 70 - 10 + '%',
              left: 0,
              right: 0,
            }"
          >
            <div class="text-h1 text-white">Web Development</div>
            <q-card class="my-card text-center .shadow-24">
              <q-img
                src="~assets\data_science.jpg"
                alt=""
                spinner-color="white"
                style="height: 140px; max-width: 300px"
              />

              <q-card-section style="max-width: 300px">
                I have found that focusing on web development allows me to build
                beautiful, easy to use, and responsive applications that can be
                used on many modern devices.
              </q-card-section>
            </q-card>
          </div>
        </template>
      </q-parallax>
    </section>
    <section class="q-gutter-xl">
      <q-parallax>
        <template v-slot:content="scope">
          <div
            class="q-gutter-xl absolute row justify-center items-center"
            :style="{
              top: scope.percentScrolled * 70 - 10 + '%',
              left: 0,
              right: 0,
            }"
          >
            <div class="text-h1 text-white">Education</div>
            <q-card class="my-card text-center .shadow-24">
              <q-img
                src="~assets\data_science.jpg"
                alt=""
                spinner-color="white"
                style="height: 140px; max-width: 300px"
              />

              <q-card-section style="max-width: 300px">
                University of Glasgow opened up the world of computer science to
                me. I got introduced to thousands concepts that range from cyber
                security to UI design, from machine-level language to neural
                networks.
              </q-card-section>
            </q-card>
          </div>
        </template>
      </q-parallax>
    </section>
    <section class="q-gutter-xl">
      <q-parallax>
        <template v-slot:content="scope">
          <div
            class="q-gutter-xl absolute row justify-center items-center"
            :style="{
              top: scope.percentScrolled * 70 - 10 + '%',
              left: 0,
              right: 0,
            }"
          >
            <div class="text-h1 text-white">My background</div>
            <q-card class="my-card text-center .shadow-24">
              <q-img
                src="~assets\data_science.jpg"
                alt=""
                spinner-color="white"
                style="height: 140px; max-width: 300px"
              />

              <q-card-section style="max-width: 300px">
                Coming from a family of engineers, I was always interested in
                understanding new technologies to be able to create convenient
                and efficient solutions. I was born and raised in Egypt midst a
                large family, although my passion for technology forced me to
                travel abroad to experience cutting-edge technologies first
                hand.
              </q-card-section>
            </q-card>
          </div>
        </template>
      </q-parallax>
    </section>
  </div>
</template>

<style lang="scss">
// ::-webkit-scrollbar {
//   display: none;
// }
body {
  background-color: rgb(100, 100, 100);
  scroll-behavior: smooth;

  .container {
    height: 100vh;

    scroll-snap-type: y proximity;
    overflow-y: scroll;

    section {
      display: flex;
      justify-content: center;
      align-items: center;

      height: 100vh;
      scroll-snap-align: center;
      scroll-snap-stop: always;

      &:nth-of-type(1) {
        background-color: $primary;
      }

      &:nth-of-type(2) {
        background-color: $secondary;
      }

      &:nth-of-type(3) {
        background-color: $primary;
      }
      &:nth-of-type(4) {
        background-color: $secondary;
      }
      &:nth-of-type(5) {
        background-color: $primary;
      }
    }
  }
}
</style>
