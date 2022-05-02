<template>

<div class="flex">

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
