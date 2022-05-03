<template>

<div class="row no-gutters">
    <div class=" col-4 text-white winter text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h6 class="fw-light text-uppercase">stylish and warm</h6>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase text-white rounded-pill border border-white my-4">view more</button>
        
    </div>

    <div class="spring col-4 text-white text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h6 class="fw-light text-uppercase">bright and colorful</h6>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase text-white rounded-pill border border-white my-4">view more</button>
        
    </div>

    <div class="autumn col-4 text-white text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h6 class="fw-light text-uppercase">rich and comfortable</h6>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase text-white rounded-pill border border-white my-4">view more</button>
        

    </div>

</div>
    
</template>

<script>
export default {
  name: 'MainCollection',
}
</script>


<style scoped>

.winter{
    background-image: url('../../assets/winter_collection_bg.jpg');
    height: 400px;
    background-size: cover;
    background-repeat: no-repeat;
}

.spring{
    background-image: url('../../assets/spring_collection_bg.jpg');
    height: 400px;
    background-size: cover;
    background-repeat: no-repeat;
}

.autumn{
    background-image: url('../../assets/autumn_collection_bg.jpg');
    height: 400px;
    background-size: cover;
    background-repeat: no-repeat;
}

</style>

