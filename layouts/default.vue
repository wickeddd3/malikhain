<template>
  <v-app>
    <AppBar />
    <v-main class="fill-height">
      <Nuxt />
    </v-main>
    <AppFooter />
  </v-app>
</template>

<script>
import AppBar from '../components/app/AppBar.vue';
import AppFooter from '../components/app/AppFooter.vue';

export default {
  name: 'DefaultLayout',
  components: {
    AppBar,
    AppFooter,
  },
};
</script>
