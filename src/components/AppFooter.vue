<script>

export default {
  name:'AppFooter',
}

</script>


<template>
  <footer>
    <h3>SIGN-UP NOW</h3>
    <nav class="social">
      <ul>
        <li><img src="../assets/img/footer-facebook.png" alt=""></li>
        <li><img src="../assets/img/footer-twitter.png" alt=""></li>
        <li><img src="../assets/img/footer-youtube.png" alt=""></li>
        <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
        <li><img src="../assets/img/footer-periscope.png" alt=""></li>

      </ul>
    </nav>
  </footer>


  
</template>



<style lang="scss" scoped>

footer {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: black;
  height: 100px;
  width: 100%;
h3 {
  color: white;
  

}

ul{
  display: flex;
  list-style: none;
}
li {
  padding-left: 20px;
}
}

</style>