<template>
  <div class="my-3 col-3">
      
      <img :src="`../../assets/${image}`" alt="" class="img-fluid">
      <h5 class="text-white my-3">{{name}} </h5>
      <h6>{{tags}}</h6>
      <p>{{price}}</p>
    
  </div>
</template>

<script>
export default {
  name: 'TripleProps',
   props: {
      image: String,
      name: String,
      tags: String,
      price: String
   }
}
</script>


<style scoped>
</style>[