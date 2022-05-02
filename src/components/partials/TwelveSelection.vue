<template>

    <div class="container d-flex justify-content-center align-items-center">

      <div class=" col-3">
        <h4 class="text-uppercase">featured</h4>
      <TwelveProps
      v-for="(element, index) in featuredPro"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />
      </div>

      <div class=" col-3">
        <h4 class="text-uppercase">on sale</h4>
      <TwelveProps
      v-for="(element, index) in onSale"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />

      </div> 

      <div class=" col-3">
        <h4 class="text-uppercase">top rated</h4>
      <TwelveProps
      v-for="(element, index) in topRated"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />

      </div> 

      <div class=" col-3">
        <h4 class="text-uppercase">latest reviews</h4>
      <TwelveProps
      v-for="(element, index) in latestReviews"
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
  name: 'TwelveSelection',
  components: {
    TwelveProps
  },
  data() {
      return{
        featuredPro:[{
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "",
    "price": "$200"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Modern blabla",
    "stars": "",
    "price": "$200"
  },
    ],
      onSale:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "",
    "price": "$200"
  },
  ],
      topRated:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  ],
      latestReviews:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern blabla",
    "stars": "5",
    "price": "$200"
  },  
]
    }
      
  }
}
</script>



<style scoped>


</style>