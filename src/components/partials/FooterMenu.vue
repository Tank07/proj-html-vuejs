<template>

  <div class="bgk">

      <div class="container d-flex justify-content-around py-5">

      <FooterMenuOne/>   
      <FooterMenuTwo/>
      <FooterMenuThree/>
      <FooterMenuFour/>  

    </div>

  </div>
    
</template>

<script>

import FooterMenuOne from "./FooterMenuOne.vue"
import FooterMenuTwo from "./FooterMenuTwo.vue"
import FooterMenuThree from "./FooterMenuThree.vue"
import FooterMenuFour from "./FooterMenuFour.vue"

export default {
  name: 'FooterMenu',
  components: {
    FooterMenuOne,
    FooterMenuTwo,
    FooterMenuThree,
    FooterMenuFour
  },
   
}
</script>



<style scoped>

.bgk{
  background-color: #2b2e32;
}


</style>