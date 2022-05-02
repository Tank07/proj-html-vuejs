<template>

<div>
  <MainJumbo/>
  <DividerUno/>
  <TripleSelection/>
  <MainCollection/>
  <DividerDue/>
  <h3 class="text-center">Manca slider</h3>
  <MainDoubleImage/>
  <DividerTre/>
  <h3 class="text-center">Manca Slider</h3>
  <MainPromotion/>
  <DividerQuattro/>
  <BlogImages/>
  <hr>
  <TwelveSelection/>
  
</div>
    
</template>

<script>

import MainJumbo from './partials/MainJumbo.vue'
import DividerUno from './partials/DividerUno.vue'
import TripleSelection from './partials/TripleSelection.vue'
import MainCollection from './partials/MainCollection.vue'
import DividerDue from './partials/DividerDue.vue'
import MainDoubleImage from './partials/MainDoubleImage.vue'
import DividerTre from './partials/DividerTre.vue'
import MainPromotion from './partials/MainPromotion.vue'
import DividerQuattro from './partials/DividerQuattro.vue'
import BlogImages from './partials/BlogImages.vue'
import TwelveSelection from './partials/TwelveSelection.vue'

export default {
  name: 'MainProj',
 components: {
    MainJumbo,
    DividerUno,
    TripleSelection,
    MainCollection,
    DividerDue,
    MainDoubleImage,
    DividerTre,
    MainPromotion,
    DividerQuattro,
    BlogImages,
    TwelveSelection
  }
}
</script>


<style scoped lang="scss">

</style>
