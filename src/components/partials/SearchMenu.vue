<template>
  <div class="d-flex justify-content-center align-items-center py-2">
 
    <ul class="d-flex m-0 p-0">
      <li v-for="(element, index) in menuSearch" :key='index'>
        <a class="px-2 text-muted" :href="`${element.url}`">{{element.name}} <i class="fa-solid fa-angle-down text-muted fa-2xs"></i></a>
      </li>
      
    </ul>

    <p class="button_blue text-white ">SHOP NOW!</p>

    <i class="fa-solid fa-magnifying-glass px-3"></i>

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
          name: 'Products',
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

.button_blue{
  padding: 10px;
  background-color: #427ed5;
  border-radius: 20px;
}

</style>