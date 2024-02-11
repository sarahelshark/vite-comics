<script>
import AppJumbotron from "./App.Jumbotron.vue";
import ComicsList from "./ComicsList.vue";
export default {
  name: "App",
  data() {
    return {
    
    };
  },
  components: { AppJumbotron, ComicsList },
};
</script>

<template>
  <main>
    <!--Jumbotron-->
    <AppJumbotron></AppJumbotron>

    <!--Comics section-->
    <ComicsList></ComicsList>
    <!--banner-->
  </main>
</template>

<style scoped>
.comics {
  & h3 {
    display: inline-block;
    padding: 1rem 2rem;
    background-color: var(--dc-primary);
    margin: -2rem 0 0.5rem;
  }
  & img {
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: top;
  }
}
.load_more {
  text-align: center;
  margin: 2rem 0 1rem;
  justify-content: center;
  width: 100%;

  & > button {
    background-color: var(--dc-primary);
    color: var(--dc-light);
    padding: 0.5rem 2rem;
    border-style: none;
  }
}
</style>
