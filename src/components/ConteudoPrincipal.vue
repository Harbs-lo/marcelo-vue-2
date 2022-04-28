<script>
import NovoComponente from "@/components/NovoComponente.vue";
export default {
  components: {
    NovoComponente,
  },
  data() {
    return {
      professores: ["Eduardo", "Ivo", "Marco"],
    };
  },
};
</script>
<template>
  <main id="content">
    <NovoComponente titulo="Aluno" :nome="['Marcelo', 'Greg', 'Gobetti']" />
    <NovoComponente titulo="Professores" :nome="professores" />
    <NovoComponente />
    <NovoComponente />
    <NovoComponente />
    <NovoComponente />
  </main>
</template>
<style></style>
