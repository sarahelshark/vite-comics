<script>
import AppJumbotron from "./App.Jumbotron.vue";
import ComicsList from "./ComicsList.vue";
import DcBanner from "./DcBanner.vue";
export default {
  name: "App",
  data() {
    return {};
  },
  components: { AppJumbotron, ComicsList, DcBanner },
};
</script>

<template>
  <main>
    <!--Jumbotron-->
    <AppJumbotron></AppJumbotron>

    <!--Comics section-->
    <ComicsList></ComicsList>

    <!--banner-->
    <DcBanner></DcBanner>
  </main>
</template>

<style scoped>
</style>
