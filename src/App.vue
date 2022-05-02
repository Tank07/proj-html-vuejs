<template>
  <div id="app" class="my-5">
    
    <HeaderProj/>
    <hr>
    <SearchBar/>
    <MainProj/>

  </div>
</template>

<script>

import "bootstrap"

import HeaderProj from './components/HeaderProj.vue'
import SearchBar from './components/SearchBar.vue'
import MainProj from './components/MainProj.vue'

export default {
  name: 'App',
  components: {
    HeaderProj,
    SearchBar,
    MainProj
  }
}
</script>

<style lang="scss">

ul {
    list-style-type: none;
}

a {
    color: black;
    text-decoration: none;
}


@import "bootstrap/dist/css/bootstrap.min.css";

</style>
