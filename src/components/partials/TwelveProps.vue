<template>
  <div class="my-3 col-3">

      <h5 class="my-3">{{name}} </h5>
      <p><i class="fa-star" v-for="i in 5" :key="i" :class="(i <= `${stars}`) ? 'fa-solid' : 'd-none'" ></i></p>
      <p>{{price}}</p>

      <div>
      <img :src="`../../assets/${image}`" alt="" class="img-fluid">
      </div>
    
  </div>
</template>

<script>
export default {
  name: 'TwelveProps',
   props: {
      image: String,
      name: String,
      stars: String,
      price: String
   }
}
</script>


<style scoped>
</style>[