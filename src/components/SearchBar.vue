<template>

<div class="d-flex container justify-content-between align-items-center">

  <SearchLogo/>
  <SearchMenu/>

</div>
    
</template>

<script>

import SearchLogo from './partials/SearchLogo.vue' 
import SearchMenu from './partials/SearchMenu.vue'

export default {
  name: 'SearchBar',

  components: {
    SearchLogo,
    SearchMenu    
  },

  props: {
    
  }
}
</script>


<style scoped lang="scss">

</style>
