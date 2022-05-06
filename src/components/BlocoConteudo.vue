<script>
export default {
  data() {
    return {
      imagem: [new URL("./imagens/gato1.jpg", import.meta.url).href],
    };
  },
  props: {
    titulo: {
      default: "A definir",
    },

    info: Array,
  },
};
</script>
<template>
  <article class="block">
    <div class="essa">
      <img :src="imagem[0]" class="fotoAjude" />
      <h1 class="titu">{{ titulo }}</h1>
    </div>
    <hr />
    <ul>
      <li v-for="(info, i) of info" :key="i">{{ info }}</li>
    </ul>
  </article>
</template>
<style></style>
