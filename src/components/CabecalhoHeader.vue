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
      <ul>
        <li></li>
        <img :src="imagem" class="logo" />
        <li class="animais">animais</li>
        <li class="ajude">ajude</li>
        <li class="denuncie">denuncie</li>
        <li><input type="text" name="" class="pesquisar" /></li>
        <li><img class="login" src="./imagens/login2.png" /></li>
      </ul>
    </div>
  </header>
</template>

<style></style>
