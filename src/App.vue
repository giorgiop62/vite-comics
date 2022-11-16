
<script>

import AppHeader from './components/AppHeader.vue';
import links from './data/menu';

export default {
  name:'App',
  components: {
    AppHeader,
    
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
  
</template>



<style lang="scss">



</style>