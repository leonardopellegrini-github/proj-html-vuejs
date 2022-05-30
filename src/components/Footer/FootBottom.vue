<template>
  <div>
    <div class="footbot d-flex align-items-center">

    <div class="container">
      <div class="row d-flex justify-content-around align-items-center">
        <div class="col-8">
          <p>© Copyright 2012 - 2022 | Avada Theme by <b>ThemeFusion</b> | All Rights Reserved | Powered by <b>WordPress</b></p>
        </div>
        <div class="col-4 d-flex justify-content-around align-items-center">
          <ul class="social">
            <li><i class="tondo fa-brands fa-facebook-f"></i></li>
            <li><i class="tondo fa-brands fa-twitter"></i></li>
            <li><i class="tondo fa-brands fa-instagram"></i></li>
            <li><i class="tondo fa-brands fa-youtube"></i></li>
          </ul>
        </div>
      </div>
    </div>

  </div>
  </div>
</template>

<script>
export default {
  name: 'FootBottomVue',
}
</script>

<style lang="scss" scoped>



li{
  text-decoration: none;
   margin-right: 10px;
  display:inline;
}

.footbot{
  height:100px;
  border-top: 1px solid rgba(59, 59, 59, 0.316);

  p, .social{
    margin: 0;
  }
  .tondo{
    padding: 20px;
    margin: 5px;
    font-size: 20px;
    border-radius: 50px;
    color: white;
  }

  .fa-facebook-f{
    background-color: #3B5998;
    padding: 20px 22px;
  }
  .fa-twitter{
    background-color: #55ACEE;
  }
  .fa-instagram{
    background-color: #3F729B;
  }
  .fa-youtube{
    background-color: #CD201F;
  }

}

</style>