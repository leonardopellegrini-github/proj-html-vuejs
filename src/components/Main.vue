<template>
  <div>
    <BioVue/>
    <LatestTitleVue/>
    <LastestPostsVue/>
    <BlackBandVue titleBand="READ OUR BLOG"/>
    <ForumSectionVue/>
    <BlackBandVue titleBand="GO TO OUR FORUM"/>
    <JoinCommVue />
    <NewsLetterVue />
  </div>
</template>

<script>

import BioVue from './Main/Bio.vue'
import LatestTitleVue from './Main/LatestTitle.vue'
import LastestPostsVue from './Main/LastestPosts.vue'
import BlackBandVue from './Main/BlackBand.vue'
import ForumSectionVue from './Main/ForumSection.vue'
import JoinCommVue from './Main/JoinComm.vue'
import NewsLetterVue from './Main/Newsletter.vue'

export default {
  name: 'MainVue',
  components:{
    BioVue,
    LatestTitleVue,
    LastestPostsVue,
    BlackBandVue,
    ForumSectionVue,
    JoinCommVue,
    NewsLetterVue,
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
  transition: all 0.5s ease;
  &:hover{
    background-color: #27AABE;
    animation-duration: 0.6s;
    transition-timing-function: ease;
  }
  h4{
    color: white;
    font-size: 15px;
    font-weight: 700;
    text-transform: uppercase;
  }
}

</style>