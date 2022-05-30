<template>
  <div>
      <FootTopVue />
      <FootBottomVue />
  </div>
</template>

<script>

import FootTopVue from './Footer/FootTop.vue'
import FootBottomVue from './Footer/FootBottom.vue'

export default {
  name: 'FooterVue',
  components:{
    FootTopVue,
    FootBottomVue
  }
}
</script>

<style>

</style>