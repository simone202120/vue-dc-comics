<template>
  <div class="container">
    <img src="../assets/jumbotron.jpg" alt="">
  </div>
</template>

<script>
    
  export default {
    name:'MyJumbotron',
  }
</script>

<style scoped lang="scss">
  .container{
    height: 400px;
    img{
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: top;
    }
  }
</style>