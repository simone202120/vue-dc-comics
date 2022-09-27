<template>
    <div class="cardFumetto">
        <img :src="details.thumb" alt="">
        <h6>{{details.series}}</h6>
    </div>
</template>

<script>
export default {
    name:'GeneraFumetto',
    props:{
            details:Object
        }
}
</script>

<style lang="scss" scoped>

.cardFumetto{
      width: calc(100% / 6);
      height: 150px;
      color: white;
      padding: 0 10px;
      margin-top: 30px;

      &:hover{
        scale: 1.1;
      }

      img{
        width: 100%;
        object-fit: cover;
        object-position: top;
        height: 100%;
      }
    }

</style>