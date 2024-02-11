<script>
import AppJumbotron from './App.Jumbotron.vue';

export default {
    name: "App",
    data() {
        return {
        };
    },
    components: { AppJumbotron }
};
</script>

<template>
  <main>
    <!--Jumbotron-->
    <AppJumbotron></AppJumbotron>

    <!--Comics section-->
    <section class="comics">
      
      <div class="container">
        <h3>Current Series</h3>
        <div class="row">
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>
          <div class="col-12 col-md-4 col-lg-2">
            
            <div class="card">
              <img src="https://picsum.photos/200/200" alt="">
              <h5>lorem</h5>
            </div>
          </div>

        </div>
      </div>
    </section>
    <!--banner-->
  </main>
</template>

<style scoped>

.container{
  flex-direction: column;
}

</style>
