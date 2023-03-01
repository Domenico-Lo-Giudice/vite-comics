<script>
// import componenti
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppIconsContent from "./components/AppIconsContent.vue";
import AppFooter from "./components/AppFooter.vue";

//definizione componenti
export default {
  data() {
    return {
      title: "ViteComics",
    };
  },

  components: {
    AppHeader,
    AppContent,
    AppIconsContent,
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <AppContent products="products" />
  <AppIconsContent />
  <AppFooter />
</template>

<style lang="scss">
@use "./assets/scss/general.scss";
</style>
