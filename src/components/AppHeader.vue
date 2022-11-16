
<script>
export default {
  name:'AppHeader',
  props:{
    menu:Array
  },
  data(){
    return{

    }
  }
}
</script>

<template>
  <header>
    <div class="logo">
      <img src="/dc-logo.png" alt="">
    </div>

    <nav>
      <ul>
        <li v-for="(link, index) in menu" :key="index"> 
          {{ link.text }}
        </li>
      
      </ul>
    </nav>

  </header>
  
</template>



<style lang="scss">

header {
  background-color: yellow;
  ul {
    display: flex;
    li {
      padding: 10px;
      &:hover {
        background-color: green;
      }
    }
  }
}

</style>