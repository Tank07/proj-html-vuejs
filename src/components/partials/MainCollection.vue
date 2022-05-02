<template>

<div class="row no-gutters">
    <div class=" col-4 winter text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h4>RIch adn kfadakdka</h4>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase">view more</button>
        
    </div>

    <div class="spring col-4 text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h4>RIch adn kfadakdka</h4>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase">view more</button>
        
    </div>

    <div class="autumn col-4 text-center flex flex-column justify-content-end align-items-center">

        <h1>Winter Collection</h1>
        <h4>RIch adn kfadakdka</h4>
        
        <button type="button" class="btn btn-outline-secondary text-uppercase">view more</button>
        

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

