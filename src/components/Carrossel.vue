<template>
  <b-container>
    <b-carousel
      controls
      indicators
      label-next=""
      label-prev=""
    >
      <b-carousel-slide img-src="https://compjunior.com.br/api/files/images/screenshot20210415-juridica-jr1.png"
        caption="Jurídica Jr"
        text="Desenvolvimento de uma página web para a empresa júnior de Direito da UFLA mostrando sua carta
        de serviços."
        style="text-shadow: 1px 1px 2px #333;"
      ></b-carousel-slide>
      <b-carousel-slide class="imagem2" img-src="https://compjunior.com.br/api/files/images/screenshot20210415-se7i.png"
        caption="SE7I"
        text="Desenvolvimento de um sistema de organização de eventos que permite a visualização de palestras
        e inscrições e no fim do evento, gerar um certificado."
        style="text-shadow: 1px 1px 2px #333;"
      ></b-carousel-slide>
      <b-carousel-slide img-src="https://compjunior.com.br/api/files/images/portfoliocomp20anos011.png"
        caption="Comp 20 Anos"
        text="Desenvolvimento de um aplicativo mobile para verificar a presença das pessoas em palestras
        através da leitura de QR Code."
        style="text-shadow: 1px 1px 2px #333;"
      ></b-carousel-slide>
    </b-carousel>
  </b-container>
</template>

<script>
export default {
    name: "Carrossel",
};
</script>

<style scoped>

</style>

