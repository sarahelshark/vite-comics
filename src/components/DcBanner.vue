<script>
export default {
  name: 'DcBanner',
  data() {
    return {
      items: [
        {
          text: 'Digital comics',
          icon: '/img/buy-comics-digital-comics.png'
        },
        {
          text: 'DC merchandise',
          icon: '/img/buy-comics-merchandise.png'
        },
        {
          text: 'Subscription',
          icon: '/img/buy-comics-subscriptions.png'
        },
        {
          text: 'Comic shop location',
          icon: '/img/buy-comics-shop-locator.png'
        },
        {
          text: 'DC power visa',
          icon: '/img/buy-comics-digital-comics.png'
        }
      ]
    }
  },
  methods: {
    /* Only if image are placed inside /src/assets/ */
    getImageUrl(name) {
      console.log(new URL(`../assets/img/${name}.png`, import.meta.url));
      return new URL(`../assets/img/${name}.png`, import.meta.url).href
    }
    /*studio STATIC ASSET HANDLING in vue docs */
  }
}
</script>
<template>
  <div class="banner">
    <div class="container">
      <div class="item" v-for="item in items">
        <img height="60" :src="item.icon" alt="">
        <span>{{item.text}}</span>
      </div>
    </div>
  </div>
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
      gap: .5rem;
    }
  }
  
</style>