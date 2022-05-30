<template>
  <div id="comm" class="d-flex justify-content-center align-items-center flex-column">
    <h1>HEY! Join to Our Community</h1>
    <p>
      Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>
      Lorem Ipsum is simply dummy text of the printing and typesetting industry.
    </p>
    <a href="#">Sign Up <i class="fa-solid fa-angle-right"></i></a>
  </div>
</template>

<script>
export default {
  name: 'JoinCommVue'
}
</script>

<style lang="scss" scoped>

#comm{
  background-image: url(@/assets/img/join_now_cta_bg.jpg);
  background-size: cover;
  height: 400px;
  color: white;
}

h1{
  font-size: 40px;
  font-weight: 700;
}

p{
  padding: 20px;
}

a{
  padding:20px;
  background-color: #27AABE;
  font-size: 20px;
  text-decoration: none;
  color: white;
  font-weight: 600;
  text-transform: uppercase;
}

</style>