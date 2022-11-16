<template>
  <pesquisar />
  <produtos />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import pesquisar from "./Loja/pesquisar.vue";
import produtos from "./Loja/produtos.vue";

export default defineComponent({
  name: "MinhaLoja",
  components: {
    pesquisar,
    produtos,
  },
});
</script>

<style scoped>
h1 {
  color: gold;
}
</style>
