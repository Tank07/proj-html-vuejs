<template>

    <div class="d-flex justify-content-center align-items-center text-white">

      <div class="">
        <h6 class="text-uppercase fw-normal">Top Rated Products</h6>
      <TwelveProps
      v-for="(element, index) in topRated"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />
      </div>

  </div>
    
</template>

<script>
import TwelveProps from "./TwelveProps.vue"
export default {
  name: 'FooterMenuTwo',
  components: {
    TwelveProps
  },
  data() {
      return{
       topRated:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Leather Gloves",
    "stars": "5",
    "price": "$45"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Spring Printed Dress",
    "stars": "5",
    "price": "$47"
  },
  ]
      }
  }
}
</script>



<style scoped>


</style>