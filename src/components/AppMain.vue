<script>
import AppJumbotron from "./App.Jumbotron.vue";
import ComicsList from "./ComicsList.vue";
export default {
  name: "App",
  data() {
    return {};
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
    <div class="banner">
      <div class="container">
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
        <div class="item">
          <img height="60" src="/img/buy-comics-digital-comics.png" alt="" />
          <span>Digital comics</span>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.banner {
  background-color: var(--dc-primary);
  padding: 2rem 0;

  & > .container {
    display: flex;
    gap: 1rem;
    justify-content: space-evenly;
  }
  & .item {
    display: flex;
    align-items: center;
    gap: 1rem;
  }
}
</style>
