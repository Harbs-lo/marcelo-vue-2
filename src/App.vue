<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoCima from "@/components/CabecalhoCima.vue";
import ConteudoPrincipal from "@/components/ConteudoPrincipal.vue";
import FooterBaixo from "@/components/FooterBaixo.vue";
export default {
  components: {
    MenuLateral,
    CabecalhoCima,
    ConteudoPrincipal,
    FooterBaixo,
  },
};
</script>
<template>
  <MenuLateral />
  <CabecalhoCima />
  <ConteudoPrincipal />
  <FooterBaixo />
</template>
<style></style>
