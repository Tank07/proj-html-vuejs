<template>

<div class="d-flex align-items-center justify-content-center py-5">

    <i class="fa-solid fa-angle-left px-2 py-3 bg_angle"></i>
    <div class="cart_hov"> <div class="text_hover d-flex flex-column justify-content-center align-items-center"><p>Modern Lovee tree</p> <p>Women T-Shirts</p> <p>68$</p> <i class="fa-solid fa-cart-shopping fa-2xs"></i><span class="">Add to cart</span> <i class="fa-solid fa-list fa-2xs"></i> Add to list</div></div>
    
    <img src="../../assets/modern_love_tee-200x260.jpg" alt="" class="img-fluid cart_hov"> 
    <img src="../../assets/black_elegant_leather_jacket-200x260.jpg" alt="" class="img-fluid"> 
    <img src="../../assets/black_leather_jacket-200x260.jpg" alt="" class="img-fluid"> 
    <img src="../../assets/hipster_black_top-200x260.jpg" alt="" class="img-fluid"> 

    <i class="fa-solid fa-angle-right px-2 py-3 bg_angle"></i>

</div>
  

    
</template>

<script>
export default {
  name: 'SliderSmall',
  data() {
      return{
          hover:false, 
    
    }
  }
}
</script>


<style scoped>

.bg_angle{
    background-color: #c1c1c1;
}

.cart_hov{
  background-image: url("../../assets/spring_printed_dress-200x260.jpg");
  height: 260px;
  width: 200px;
  position: relative;
}

.cart_hov:hover div{
 width: 150px;
 padding: 8px 15px;
 visibility: visible;
 opacity: 0.7; 
}

.text_hover{
  position: absolute;
  background: rgb(63,94,251, 0.5);
  background: radial-gradient(circle, rgba(63,94,251,1) 0%, rgba(252,70,107,1) 100%);
  color: white;
  visibility: hidden;
  width: 100%;
  height: 100%;
}

</style>

