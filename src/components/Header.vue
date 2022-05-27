<template>
  <div>
    <MenuVue/>
    <JumbotronVue/>
  </div>
  
</template>

<script>

import MenuVue from './Header/Menu.vue'
import JumbotronVue from './Header/Jumbotron.vue'

export default {
  name: 'HeaderVue',
  components:{
    MenuVue,
    JumbotronVue,
}
  
}
</script>

<style scoped lang="scss">

</style>
