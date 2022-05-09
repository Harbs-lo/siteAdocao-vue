<script>
import CabecalhoHeader from "@/components/CabecalhoHeader.vue";
import BlocoRodape from "./components/BlocoRodape.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
import BlocoLateral from "./components/BlocoLateral.vue";
export default {
  components: {
    CabecalhoHeader,
    BlocoRodape,
    BlocoPrincipal,
    BlocoLateral
},
};
</script>

<template>
  <CabecalhoHeader />
  <BlocoRodape />
  <BlocoPrincipal />
  <BlocoLateral />
</template>

<style></style>
