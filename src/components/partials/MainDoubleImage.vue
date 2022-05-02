<template>

<div class="flex container">
    <div class="container promo1 text-left flex flex-column justify-content-center align-items-start mx-4">

        <h1>Winter Collection</h1>
        <h4>RIch adn kfadakdka</h4>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase">view more</button>
        
    </div>

    <div class="container promo2 text-left flex flex-column justify-content-center align-items-start">

        <h1>Winter Collection</h1>
        <h4>RIch adn kfadakdka</h4>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase">view more</button>
        
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
    height: 250px;
    background-size: cover;
    background-repeat: no-repeat;
}

.promo2{
    background-image: url('../../assets/promo_box_2_bg.jpg');
    height: 250px;
    background-size: cover;
    background-repeat: no-repeat;
}

</style>

