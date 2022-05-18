<script>
import MenuLateral from "@/components/MenuLateral.vue";
import ConstCabecalho from "@/components/ConstCabecalho.vue";
import ConstRodape from "@/components/ConstRodape.vue";
import { RouterView } from 'vue-router'

export default {
  components: { MenuLateral, ConstCabecalho, ConstRodape, RouterView },
};
</script>
<template>
  <MenuLateral />
  <ConstCabecalho />
  <main id="content">
    <RouterView />
  </main>
  <ConstRodape />
  
</template>
<style></style>
