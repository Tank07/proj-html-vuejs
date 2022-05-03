<template>

    <div class="container d-flex justify-content-around py-5">

      <div class=" ">
        <h5 class="text-uppercase fw-normal">featured</h5>
      <TwelveProps
      v-for="(element, index) in featuredPro"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />
      </div>

      <div class=" ">
        <h5 class="text-uppercase fw-normal">on sale</h5>
      <TwelveProps
      v-for="(element, index) in onSale"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />

      </div> 

      <div class=" ">
        <h5 class="text-uppercase fw-normal">top rated</h5>
      <TwelveProps
      v-for="(element, index) in topRated"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :price = "element.price"
      />

      </div> 

      <div class="">
        <h5 class="text-uppercase fw-normal">latest reviews</h5>
      <TwelveProps
      v-for="(element, index) in latestReviews"
      :key ="index"
      :image = "element.image"
      :name = "element.name"
      :stars = "element.stars"
      :admin = "element.admin"
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
    "name": "Black Jacket",
    "stars": "",
    "price": "$125"
  },
  {
    "image":"black_leather_suit-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "5",
    "price": "$200"
  },
  {
    "image":"blue_jacket_and_white_stripe_tee-200x260.jpg",
    "name": "Hipster Black Top",
    "stars": "",
    "price": "$57"
  },
    ],
      onSale:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "5",
    "price": "$200"
  },
  {
    "image": "black_elegant_leather_jacket-200x260.jpg",
    "name": "Blue Leather Jacket",
    "stars": "",
    "price": "$80"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Modern Leather Boots",
    "stars": "",
    "price": "$30"
  },
  ],
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
  ],
      latestReviews:[{
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Black Leather Jacket",
    "stars": "5",
    "admin": "by admin"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Leather Gloves",
    "stars": "5",
    "admin": "by Beardman"
  },
  {
    "image":"modern_black_leather_suit-200x260.jpg",
    "name": "Spring Printed Dress",
    "stars": "5",
    "admin": "by admin"
  },  
]
    }
      
  }
}
</script>



<style scoped>


</style>