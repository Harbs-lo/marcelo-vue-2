<script>
export default {
  props: {
    titulo: {
      default: "A definir",
    },
    nome: Array,
  },
};
</script>
<template>
  <article class="block">
    <h1>{{ titulo }}</h1>
    <ul>
      <li v-for="(nome, i) of nome" :key="i">{{ nome }}</li>
    </ul>
  </article>
</template>
<style></style>
