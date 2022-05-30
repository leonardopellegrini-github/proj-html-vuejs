<template>
  <div class="blackband d-flex justify-content-center align-items-center">
    <h4>{{titleBand}} <i class="fas fa-arrow-right"></i></h4>
  </div>
</template>

<script>
export default {
  name: 'BlackBandVue',
  props:{
    titleBand: String,
  }
}
</script>

<style lang="scss">

</style>