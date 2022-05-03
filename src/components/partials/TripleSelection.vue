<template>

    <div class="container text-center">

        <div class="btn-group" role="group" aria-label="Basic example">
            <button type="button" class="btn btn-primary"> Men </button>
            <button type="button" class="btn btn-primary"
             @mouseover="hover = true"
             @mouseleave="hover = false"> Women </button>
            <button type="button" class="btn btn-primary" 
             @mouseover="otherover = true"
             @mouseleave="otherover = false"> Accessories </button>
        </div>

      <div class=" row text-center" :class="{ inactive: otherover , inactive: hover }" >
      <TripleProps
      v-for="(element, index) in tripleProducts"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :tags = "element.tags"
      :price = "element.price"
      />
      </div> 

      <div class=" row text-center" :class="(hover == true) ? 'd-flex' : 'd-none'">
      <TripleProps
      v-for="(element, index) in tripleWomen"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :tags = "element.tags"
      :price = "element.price"
      />
      </div> 

      <div class=" row text-center" :class="(otherover == true) ? 'd-flex' : 'd-none'">
      <TripleProps
      v-for="(element, index) in tripleAccessories"
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
          hover:false,
          otherover:false,
          tripleProducts:[{
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Black Leather Jacket",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$176"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Blue Jacket & Stripe Tee",
    "tags": "Men,Jackets,Suits",
    "price": "$580"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$96"
  },
],
tripleWomen:[{
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Donna",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$176"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Blue Jacket & Stripe Tee",
    "tags": "Men,Jackets,Suits",
    "price": "$580"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$96"
  },
],
tripleAccessories:[{
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Accessorio",
    "tags": "Men,Jackets,Jeans",
    "price": "$200"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$176"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Blue Jacket & Stripe Tee",
    "tags": "Men,Jackets,Suits",
    "price": "$580"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern Black Leather Suit",
    "tags": "Men,Jackets",
    "price": "$96"
  },
]
    }
      
  },
methods: {
    myFilter: function() {
      this.isActive = !this.isActive;
    }
  }

}
</script>



<style scoped>

.active{
  display: flex;
}

.inactive{
  display: none;
}


</style>