<script setup>
import CategoriasComp from "../components/CategoriasComp.vue";
</script>

<template>
  <div class="container">
    <div class="recomendados">
      <h2>Recomendados</h2>
      <div class="filmes"></div>
    </div>
    <CategoriasComp />
  </div>
</template>

<style scoped>
.container {
  display: grid;
  color: red;
  height: 100vh;
  grid-template-columns: 80% 20%;
  grid-template-areas: "recomendados categorias";
}

.recomendados {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
}

.filmes {
  background-color: white;
  border-radius: 10px;
  width: 80%;
  height: 400px;
}
</style>
