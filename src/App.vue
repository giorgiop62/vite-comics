
<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/Appmain.vue';
import AppFooter from './components/AppFooter.vue';
import links from './data/menu';

export default {
  name:'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    
  },
  data(){
    return{
      links
    }
  }

}
</script>


<template>
  <AppHeader :menu="links"/>
  <AppMain />
  <AppFooter />
  
</template>



<style lang="scss">



</style>