<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';


export default{
  name:'App',
  components:{
    AppHeader,
    AppMain,
    AppFooter,
    
},
  data(){
    return{
      message:'Hello',
    }

  },
}
</script>

<template>
   <h1>{{ message }}</h1>

   <AppHeader></AppHeader>
   <AppMain></AppMain>
   <AppFooter></AppFooter>

</template>

<style >

</style>



