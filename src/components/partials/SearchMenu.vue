<template>
  <div class="flex_bs">
 
    <ul>
      <li v-for="(element, index) in menuSearch" :key='index'>
        <a :href="`${element.url}`">{{element.name}}</a>
      </li>
      
    </ul>

    <p><span>SHOP NOW!</span></p>

    <i class="fa-solid fa-magnifying-glass"></i>

  </div>
</template>

<script>
export default {
  name: 'SearchMenu',
  data() {
    return {
      menuSearch: [
        {
          name: 'Home',
          url: ''
        },
        {
          name: 'Shop',
          url: ''
        },
        {
          name: 'Poducts',
          url: ''
        },
        {
          name: 'Categories',
          url: ''
        },
        {
          name: 'News',
          url: ''
        },
        {
          name: 'Elements',
          url: ''
        },
      ]
    }
  }
}
</script>


<style scoped >

ul{
  display: flex;
}

</style>