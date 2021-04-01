<template>
  <article>
    <p v-for="tours in toursBoucle" :key="tours">bonsoir</p>
    <br />
    <button @click="this.ajouter">plus</button>
    <!-- @ ou v-on:  les 2 ca marche / OU @click="nombre++ (sans methods:{})"-->
    <br />
    <button v-on:click="this.diminuer">moins</button>
  </article>
</template>

<script>
export default {
  data() {
    return {
      toursBoucle: 5,
      commentaires: null,
    };
  },
  beforeCreate() {
    fetch("https://jsonplaceholder.typicode.com/posts")
      .then((reponse) => reponse.json())
      .then((resultat) => console.log(resultat));
  },
  methods: {
    ajouter() {
      this.toursBoucle++;
    },
    diminuer() {
      this.toursBoucle--;
    },
  },
};
</script>

<style>
article {
  border: 1px solid black;
  margin-top: 5%;
}

article bouton {
  border: 2px solid black;
}
</style>