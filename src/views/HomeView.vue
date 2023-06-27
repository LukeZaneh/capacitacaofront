<template>
  <div class="home">
    <Navbar />
    <h1>Esta é a página inicial</h1>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style scoped>
h1 {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
</style>
