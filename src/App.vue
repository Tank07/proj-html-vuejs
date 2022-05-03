<template>
  <div id="app" class="">
    
    <HeaderProj/>
    <hr>
    <SearchBar/>
    <MainProj/>
    <FooterProj/>

  </div>
</template>

<script>

import "bootstrap"

import HeaderProj from './components/HeaderProj.vue'
import SearchBar from './components/SearchBar.vue'
import MainProj from './components/MainProj.vue'
import FooterProj from './components/FooterProj.vue'

export default {
  name: 'App',
  components: {
    HeaderProj,
    SearchBar,
    MainProj,
    FooterProj
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

hr{
  margin: 0;
}

p{
  margin: 0;
}


@import "bootstrap/dist/css/bootstrap.min.css";

</style>
