<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/Appmain.vue';
import AppFooter from './components/Appfooter.vue';

  export default {
    name:'App',
    components:{
      AppHeader,
      AppMain,
      AppFooter
    }
  
  }
</script>


<template>
  <AppHeader />
  <AppMain />
  <AppFooter />

  
</template>


<style>

</style>