<template>

<div>
  <MainJumbo/>
  <DividerUno/>
  <TripleSelection/>
  <MainCollection/>
  <DividerDue/>
  <SliderSmall/>
  <MainDoubleImage/>
  <DividerTre/>
  <SliderBig/>
  <MainPromotion/>
  <DividerQuattro/>
  <BlogImages/>
  <hr>
  <TwelveSelection/>
  <MainLogos/>
  
</div>
    
</template>

<script>

import MainJumbo from './partials/MainJumbo.vue'
import DividerUno from './partials/DividerUno.vue'
import TripleSelection from './partials/TripleSelection.vue'
import MainCollection from './partials/MainCollection.vue'
import DividerDue from './partials/DividerDue.vue'
import SliderSmall from './partials/SliderSmall.vue'
import MainDoubleImage from './partials/MainDoubleImage.vue'
import DividerTre from './partials/DividerTre.vue'
import SliderBig from './partials/SliderBig.vue'
import MainPromotion from './partials/MainPromotion.vue'
import DividerQuattro from './partials/DividerQuattro.vue'
import BlogImages from './partials/BlogImages.vue'
import TwelveSelection from './partials/TwelveSelection.vue'
import MainLogos from './partials/MainLogos.vue'

export default {
  name: 'MainProj',
 components: {
    MainJumbo,
    DividerUno,
    TripleSelection,
    MainCollection,
    DividerDue,
    SliderSmall,
    MainDoubleImage,
    DividerTre,
    SliderBig,
    MainPromotion,
    DividerQuattro,
    BlogImages,
    TwelveSelection,
    MainLogos
  }
}
</script>


<style scoped lang="scss">

</style>
