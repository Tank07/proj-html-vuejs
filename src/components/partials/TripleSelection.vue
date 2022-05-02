<template>

    <div class="container text-center">

        <div class="btn-group" role="group" aria-label="Basic example">
            <button type="button" class="btn btn-primary">Men</button>
            <button type="button" class="btn btn-primary">Women</button>
            <button type="button" class="btn btn-primary">Accessories</button>
        </div>

      <div class=" row text-center">
      <TripleProps
      v-for="(element, index) in tripleProducts"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :tags = "element.tags"
      :price = "element.price"
      />

      </div> 

  </div>
    
</template>

<script>
import TripleProps from "./TripleProps.vue"
export default {
  name: 'TripleSelection',
  components: {
    TripleProps
  },
  data() {
      return{
          tripleProducts:[{
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Black Leather Jacket",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Modern blabla",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
]
    }
      
  }
}
</script>



<style scoped>


</style>