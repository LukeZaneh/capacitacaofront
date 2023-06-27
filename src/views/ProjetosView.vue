<template>
    <div class="projeto">
      <Navbar />
      <h1>Alguns de nossos projetos</h1>
      <Carrossel />
    </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Carrossel from "@/components/Carrossel.vue"

export default {
  name: "ProjetosView",
  components: {
    Navbar,
    Carrossel,
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