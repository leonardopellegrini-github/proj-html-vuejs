<template>
  <div>
    <BioVue/>
    <LatestTitleVue/>
    <LastestPostsVue/>
    <BlackBandVue/>
    <ForumSectionVue/>
    <BlackBandVue/>
  </div>
</template>

<script>

import BioVue from './Main/Bio.vue'
import LatestTitleVue from './Main/LatestTitle.vue'
import LastestPostsVue from './Main/LastestPosts.vue'
import BlackBandVue from './Main/BlackBand.vue'
import ForumSectionVue from './Main/ForumSection.vue'

export default {
  name: 'MainVue',
  components:{
    BioVue,
    LatestTitleVue,
    LastestPostsVue,
    BlackBandVue,
    ForumSectionVue
}
}
</script>

<style lang="scss">

h3{
  text-transform: uppercase;
  font-size: 18px;
  color: #5F5F5F;
  letter-spacing: 5px;
  font-weight: 700;
}

h2{
  font-size: 35px;
  color: black;
  font-weight: 700;
}

.linearanc{
  background-color: #FC8C5E;
  height: 3px;
  width: 8%;
  border-radius: 25px;
  margin: auto;
}

.blackband{
  background-color: black;
  height: 100px;
  margin: 30px 0;
  h4{
    color: white;
    font-size: 15px;
    font-weight: 700;
    text-transform: uppercase;
  }
}

</style>