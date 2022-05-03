<template>

<div class="bg_confetti">

    <div class="flex container py-5">
        <div class="container promo1 text-left flex flex-column justify-content-center align-items-start mx-4 text-white px-5">

            <h1 class="fw-bold">70% Off</h1>
            <h6 class="fw-light">Vivamus tempo leo lacus, fegiat, <br> ut magna aliquat era. </h6 >
            
            <button type="button" class="btn btn-outline-secondary text-uppercase text-white rounded-pill border border-white my-3">view more</button>
            
        </div>

        <div class="container promo2 text-left flex flex-column justify-content-center align-items-start text-white px-5">

            <h1 class="fw-bold">Free Shipping</h1>
            <h6 class="fw-light">Vivamus tempo leo lacus, fegiat, <br> ut magna aliquat era. </h6 >
            
            <button type="button" class="btn btn-outline-secondary text-uppercase text-white rounded-pill border border-white my-3">view more</button>
            
        </div>

    </div>

</div>
    
</template>

<script>
export default {
  name: 'MainDoubleImage',
}
</script>


<style scoped>

.promo1{
    background-image: url('../../assets/promo_box_1_bg.jpg');
    height: 300px;
    background-size: cover;
    background-repeat: no-repeat;
}

.promo2{
    background-image: url('../../assets/promo_box_2_bg.jpg');
    height: 300px;
    background-size: cover;
    background-repeat: no-repeat;
}

.bg_confetti{
    background-image: url("../../assets/bkgd_confetti-compressor.jpg");
}

</style>

