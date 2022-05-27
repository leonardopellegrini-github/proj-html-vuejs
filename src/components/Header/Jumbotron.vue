<template>
  
  <div id="jumbo" class="d-flex align-items-center">
    <div class="container">
      <h1>Tech Solutions</h1>
      <h4>Discuss the latest technology</h4>
      <a href="#">Get Avada NOW</a>
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
  height: 500px;
  background-image: url(@/assets/img/home_slider_bg.jpg);
  background-position: center;
  color: white
}

a, h4, h1{
  margin-bottom: 40px
}

h1{
  font-size: 80px;
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
}

</style>