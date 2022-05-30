<template>
  
  <div id="jumbo" class="d-flex align-items-center">
    <div class="container">
      <h1>Tech Forum</h1>
      <h4>Discuss the latest technology</h4>
      <a href="#bio">Get Avada NOW</a>
    </div>
  </div>

</template>

<script>
export default {
  name: 'JumbotronVue',

}
</script>

<style scoped lang="scss">

#jumbo{
  margin-top: 15vh;
  height: 85vh;
  background-image: url(@/assets/img/home_slider_bg.jpg);
  background-position: center;
  background-attachment: fixed;
  color: white;
  bottom: 0;
}


a, h4, h1{
  margin-bottom: 40px
}

h1{
  font-size: 120px;
  font-weight: 700;
}

h4{
  font-size: 30px;
}

a{
  padding:20px;
  background-color: #27AABE;
  font-size: 20px;
  text-decoration: none;
  color: white;
  font-weight: 600;
}

</style>