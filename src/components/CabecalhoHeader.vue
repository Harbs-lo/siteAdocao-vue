<script>
export default {
  data() {
    return {
      imagem: new URL("./imagens/logo.jpg", import.meta.url).href,
    };
  },
};
</script>

<template>
  <header id="header" class="cabecalho">
    <div class="MenuHorizontal">
      <img :src="imagem" class="logo" />
      <nav class="nav-superior">
        <p class="animais">animais</p>
        <p class="ajude">ajude</p>
        <p class="denuncie">denuncie</p>
      </nav>
      <input type="text" name="" class="pesquisar" />
      <img class="login" src="./imagens/login2.png" />
    </div>
  </header>
</template>

<style></style>
