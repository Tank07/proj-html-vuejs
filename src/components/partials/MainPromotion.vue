<template>

<div>

    <div class="promotion-half">

    </div>

    <div class="promotion text-center flex flex-column justify-content-center align-items-center text-white">

        <img src="../../assets/man_testimonial.png" class="absol" alt="">
        <p class="padding_assai py-3 fst-italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque nisi perferendis quaerat in eaque alias velit eligendi laudantium exercitationem itaque dolor, deleniti deserunt fuga aspernatur modi obcaecati iste dicta aut!</p>
        <p> <span class="fw-bold">Darìo Pineda</span>, Theme Fusion</p>

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

.padding_assai{
    padding: 0 250px;
}

</style>

