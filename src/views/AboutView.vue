<template>
  <div class="about">
    <Navbar />
    <h1>Esta é a página quem somos</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "AboutView",
  components: {
    Navbar,
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


