<script>
// import componenti
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
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
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppFooter />
</template>

<style lang="scss" scoped></style>
