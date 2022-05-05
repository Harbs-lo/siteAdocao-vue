<script>
import BlocoConteudo from "./BlocoConteudo.vue";

export default {
  components: {
    BlocoConteudo,
  },
};
</script>

<template>
  <aside id="titulo">
    <h1>Ajude</h1>
  </aside>

  <main id="content">
    <BlocoConteudo
      titulo="Toto"
      img="/assets/imagens/gato1.jpg"
      :info="['Cachorro', 'Masculino', 'Essa']"
    />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
    <BlocoConteudo />
  </main>
</template>

<style></style>
