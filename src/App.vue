<script>
// import componenti
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppFooter from "./components/AppFooter.vue";

//definizione componenti
export default {
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

<style scoped></style>
