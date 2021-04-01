<template>
  <main>
    <MonArticle />
    <Tableau />
    <Meteo />
  </main>
</template>

<script>
import MonArticle from "./components/MonArticle.vue";
import Tableau from "./components/Tableau.vue";
import Meteo from "./components/Meteo.vue";

export default {
  components: {
    MonArticle,
    Tableau,
    Meteo,
  },
};
</script>

<style>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  margin: 0 auto;
}
</style>