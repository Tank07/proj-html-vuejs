<template>

<div class=" container d-flex justify-content-between align-items-center">

  <HeaderSocials/>
  <HeaderCart/>

</div>


    
</template>

<script>

import HeaderSocials from './partials/HeaderSocials.vue' 
import HeaderCart from './partials/HeaderCart.vue'

export default {
  name: 'HeaderProj',

  components: {
    HeaderSocials,
    HeaderCart    
  },

  props: {
    
  }
}
</script>


<style scoped lang="scss">

</style>
