<template>
  <the-header></the-header>
  <the-main></the-main>
  <the-footer></the-footer>
</template>

<script>
import TheFooter from "./layout/TheFooter.vue";
import TheMain from "./layout/TheMain.vue";
import TheHeader from "./layout/TheHeader.vue";
export default {
  name: "App",
  components: {
    TheFooter,
    TheMain,
    TheHeader,
  },
};
</script>

<style scoped>
@import url(./css/main.css);
#app {
  height: 100%;
}
</style>
