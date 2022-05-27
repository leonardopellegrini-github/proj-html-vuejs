<template>
  <div>
    <HeaderVue/>
    <MainVue/>
    <FooterVue/>
  </div>
  
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css'
import HeaderVue from './components/Header.vue'
import MainVue from './components/Main.vue'
import FooterVue from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HeaderVue,
    MainVue,
    FooterVue
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
}

</style>
