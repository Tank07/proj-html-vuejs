<template>

<div>

  <FooterEmail/>
  <FooterMenu/>
  <FooterPayment/>

</div>
    
</template>

<script>

import FooterEmail from './partials/FooterEmail.vue'
import FooterMenu from './partials/FooterMenu.vue'
import FooterPayment from './partials/FooterPayment.vue'

export default {
  name: 'FooterProj',
  components: {
    FooterEmail,
    FooterMenu,
    FooterPayment
    
  }
}
</script>


<style scoped >

</style>
