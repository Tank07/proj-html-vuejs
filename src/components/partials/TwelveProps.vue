<template>
  <div class="my-3">

      <p class="font_small ">{{name}} </p>
      <p><i class="fa-star py-2" v-for="i in 5" :key="i" :class="(i <= `${stars}`) ? 'fa-solid' : 'd-none'" ></i></p>
      <p class="fw-bold">{{price}}</p>
      <p class="font_small">{{admin}}</p>

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
      price: String,
      admin: String
   }
}
</script>


<style scoped>

.fa-star{
  color: #427ed5;
}

.font_small{
  font-size: 13px;
}

</style>[