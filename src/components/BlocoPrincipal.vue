<script>
import BlocoConteudo from "./BlocoConteudo.vue";

export default {
  components: {
    BlocoConteudo,
  },
  data() {
    return {
      animais: [
        { nome: 'Cat', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Dog', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Tiba', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Rex', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Toto', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'River', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Artemos', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Simba', img:"", info:['Cachorro', 'Feminino', 'Essa']},
        { nome: 'Athena', img:"", info:['Cachorro', 'Feminino', 'Essa']},
      ]
    }
  }
};
</script>

<template>
  <aside id="titulo">
    <h1>Ajude</h1>
  </aside>

  <main id="content">
    <BlocoConteudo 
      v-for="(animal, i) of animais"
      :key="i"
      :titulo="animal.nome"
      :img="animal.igm"
      :info="animal.info"
    />
  </main>
</template>

<style></style>
