<template>
  <div class="my-3 col-3">
      
      <img :src="`../../assets/${image}`" alt="" class="img-fluid">
      <h5 class="my-3 font_small">{{name}} </h5>
      <h6 class="font_smaller">{{tags}}</h6>
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

.font_small{
  font-size: 17px;
}


.font_smaller{
  font-size: 13px;
}

</style>