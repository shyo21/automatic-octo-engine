<template>
  <div>
    <div class="main-page">
      <MainPage />
    </div>
    <div class="main-page">
      <AboutVue />
    </div>
    <div class="footer">
      <Footer />
    </div>
  </div>
</template>

<script>
import MainPage from "../components/MainPage.vue";
import Footer from "../components/Footer.vue";
import AboutVue from "../components/About.vue";

export default {
  name: "Home",
  components: {
    MainPage,
    AboutVue,
    Footer,
  },
};
</script>

<style scoped></style>
