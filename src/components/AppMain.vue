<script>
import icone from '../data/icone';

export default {
  name: 'AppMain',

  data(){
    return{

    }
  }

}
</script>


<template>
  <main>
    <div class="icone"
    v-for="(icona, index) in icone" :key="index">
    </div>

  </main>
  
</template>


<style lang="scss" scoped>
.icone {
  background-color: blue;
  height: 150px;
  width: 100%;
}


</style>