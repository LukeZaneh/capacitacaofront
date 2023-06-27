<template>
    <div class="contato">
      <Navbar />
      <h1>Esta é a página de contato</h1>
    </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "ContatoView",
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