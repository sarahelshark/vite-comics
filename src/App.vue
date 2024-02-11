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
      
    }

  },
  created(){
    axios.get('https://flynn.boolean.careers/exercises/api/random/int')
    .then(function(response){
      console.log(response);
    })
  }, //potevo usare anche mounted()
}
</script>

<template>

   <AppHeader></AppHeader>
   <AppMain></AppMain>
   <AppFooter></AppFooter>

</template>

<style >

</style>



