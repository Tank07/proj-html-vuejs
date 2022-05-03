<template>

<div class="jumbo text-center flex flex-column justify-content-center align-items-center">

    <p class="text-white title_big fw-bold">Brand New Arrivals</p>
    <p class="text-white text-uppercase title_med">new collection from new york</p>
    <div class="py-3">
        <button type="button" class="btn btn-outline-secondary border border-white bg_trasp text-uppercase text-white rounded-pill fw-bolder">view all</button>
        <button type="button" class=" mx-3 btn btn-outline-secondary border border-white bg_trasp text-uppercase text-white rounded-pill fw-bolder">lookbook</button>
    </div>

</div>
    
</template>

<script>
export default {
  name: 'MainJumbo',
}
</script>


<style scoped>

.jumbo{
    background-image: url('../../assets/home1_slide_three_bg_2.jpg');
    height: 450px;
    background-size: cover;
    background-repeat: no-repeat;
}

.title_big{
    font-size: 70px;
}

.title_med{
    font-size: 20px;
}

.bg_trasp{
    background-color: rgba(255,255,255,0.3);;
}

</style>

