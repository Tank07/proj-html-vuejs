<template>

<div>

    <div class="promotion-half">

    </div>

    <div class="promotion text-center flex flex-column justify-content-center align-items-center">

        <img src="../../assets/man_testimonial.png" class="absol" alt="">
        <p>Brand New Arrivals</p>
        <p>dario pineda from new tyok</p>

    </div>
    

</div>


</template>

<script>
export default {
  name: 'MainPromotion',
}
</script>


<style scoped>

.promotion-half{
    background-image: url('../../assets/testimonials_home_1_bg.jpg');
    height: 120px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.promotion{
    background-image: url('../../assets/testimonials_home_1_bg.jpg');
    height: 300px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    position: relative;
}

.absol{
    position: absolute;
    top: -45px;
}

</style>

