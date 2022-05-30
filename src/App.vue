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
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600;700&display=swap');


*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Open Sans', sans-serif;
}



</style>
