<template>
  
  <div class="azzurro d-flex align-items-center">

    <div class="container">
      <div class="row d-flex justify-content-around">
        <div class="col-6">
          <img src="@/assets/img/logo.png" alt="Logo">
        </div>
        <div class="col-6 d-flex justify-content-around align-items-center">
          <ul class="menu">
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
          </ul>
        </div>
      </div>
    </div>

  </div>

</template>

<script>
export default {
  name: 'MenuVue'
}
</script>

<style scoped lang="scss">

.azzurro{
  background-color: #27AABE;
  color: white;
  height: 100px;
}


li{
  text-decoration: none;
   margin-right: 10px;
  display:inline;
}

</style>