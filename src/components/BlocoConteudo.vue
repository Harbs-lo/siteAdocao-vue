<script>
export default {
  props: {
    titulo: {
      default: "A definir",
    },
    img: String,
    info: Array,
  },
  setup() {
    const getImageUrl = (imagem) => {
      return new URL(`${imagem}`, import.meta.url).href;
    };
    return { getImageUrl };
  },
};
</script>
<template>
  <article class="block">
    <h1>{{ titulo }} - {{ img }}</h1>
    <hr />
    <ul>
      <li v-for="(info, i) of info" :key="i">{{ info }}</li>
    </ul>
    <img src="getImageUrl(img)" />
  </article>
</template>
<style></style>
