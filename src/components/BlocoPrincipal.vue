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
    <BlocoConteudo titulo="Toto" :info="['Cachorro', 'Masculino', 'Essa']" />

    <BlocoConteudo titulo="Tiba" :info="['Cachorro', 'Feminino', 'Essa']" />
    <BlocoConteudo
      titulo="Cat"
      img=""
      :info="['Cachorro', 'Feminino', 'Essa']"
    />
    <BlocoConteudo
      titulo="Rex"
      img=""
      :info="['Cachorro', 'Masculino', 'Essa']"
    />
    <BlocoConteudo
      titulo="Tiba"
      img=""
      :info="['Cachorro', 'Feminina', 'Essa']"
    />
    <BlocoConteudo
      titulo="Artemis"
      img=""
      :info="['Gato', 'Feminino', 'Essa']"
    />
    <BlocoConteudo
      titulo="River"
      img=""
      :info="['Cachorro', 'Feminino', 'Essa']"
    />
    <BlocoConteudo
      titulo="Simba"
      img=""
      :info="['Gato', 'Masculino', 'Essa']"
    />
    <BlocoConteudo
      titulo="Athena"
      img=""
      :info="['Cachorro', 'Feminino', 'Essa']"
    />
  </main>
</template>

<style></style>
