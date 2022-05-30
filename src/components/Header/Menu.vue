<template>
  
  <div class="azzurro d-flex align-items-center">

    <div class="container">
      <div class="row d-flex align-items-center justify-content-around">
        <div class="col-4">
          <img src="@/assets/img/logo.png" alt="Logo">
        </div>
        <div class="col">
          <ul class="menu d-flex justify-content-around align-items-center">
            <li>Home</li>
            <li>Apple</li>
            <li>Microsoft</li>
            <li>Android</li>
            <li>Forums</li>
            <li>Contact Us</li>
            <li class="button">Join Us</li>
            <li><i class="fa-solid fa-magnifying-glass"></i></li>
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
  height: 15vh;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 9;
}

ul{
  margin: 0;
  .button{
    background-color: black;
    padding: 8px;
    font-weight: 700;
    font-size: 13px;
    text-transform: uppercase;
  }
}

li{
  text-decoration: none;
   margin-right: 10px;
  display:inline;
}

</style>