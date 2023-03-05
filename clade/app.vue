<template>
  <div class="container">
    <Navbar />
    <Hero />
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import Hero from "~/components/Home/Hero.vue";
import Footer from "~/components/Footer.vue";
export default {
  name: "IndexPage",
  components: {
    Navbar,
    Hero,
    Footer,
  },
};
</script>

<style lang="scss" scoped></style>
