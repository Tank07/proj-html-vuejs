<template>

<div class="bg_dark py-5">

  <div class=" container flex justify-content-center" >

      <i class="fa-solid fa-envelope text-white"></i>
      <h4 class="text-white fw-bold px-5">Subscribe now and get special offers</h4>
      <input type="text" placeholder="insert your email" class="rounded-pill">
      <button type="button" class="btn btn-primary mx-3 rounded-pill text-uppercase px-5 fw-bold">send</button>

  </div>

</div>
    
</template>

<script>
export default {
  name: 'FooterEmail',
  props: {
    
  }
}
</script>


<style scoped>

.bg_dark{
  background-color: #303337;
}


</style>

