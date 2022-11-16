
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
  background-color: white;
  display: flex;
  align-items: center;
  justify-content: space-around;
  ul {
    display: flex;
    list-style: none;
    li {
      padding: 10px;
      &:hover {
        background-color: blue;
      }
    }
  }
}

</style>