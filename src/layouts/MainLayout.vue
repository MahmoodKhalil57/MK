<template>
  <q-layout view="hHh Lpr fFf">
    <q-header>
      <div class="q-pa-md text-white text-h5 fixed-top-left">MK</div>
    </q-header>
    <q-page-container>
      <!-- This is where pages get injected -->
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  // name: 'LayoutName',

  setup() {
    return {};
  },
};
</script>
