<template>
  
  <div class="azzurro d-flex align-items-center">

    <div class="container">
      <div class="row d-flex align-items-center justify-content-around">
        <div class="col-4">
          <img src="@/assets/img/logo.png" alt="Logo">
        </div>
        <div class="col" >
          <ul class="menu d-flex justify-content-around align-items-center">
            <li class="d-flex align-items-center" :key="`${i}`" :class="{'button' : voceMenu.bottone === true, 'hvr-bubble-bottom' : voceMenu.bottone === false}" v-for="(voceMenu, i) in vociMenu">{{voceMenu.titolo}}</li>
            <i class="fa-solid fa-magnifying-glass"></i>
          </ul>
        </div>
      </div>
    </div>

  </div>

</template>

<script>
export default {
  name: 'MenuVue',
    data(){
      return{
        vociMenu:[
          {
            titolo: "Home",
            bottone: false,
            
          },
          {
            titolo: "Apple",
            bottone: false,
          },
          {
            titolo: "Microsoft",
            bottone: false,
          },
          {
            titolo: "Android",
            bottone: false,
          },
          {
            titolo: "Forums",
            bottone: false,
          },
          {
            titolo: "Contact Us",
            bottone: false,
          },
          {
            titolo: "Join Us",
            bottone: true,
          },
         {
         //   titolo: "``",
         //   bottone: false,
         },
        ]
      }
    }
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
    height: 10vh;
    margin: 5vh;
    .hvr-bubble-bottom{
      display: none;
    }
    .hvr-bubble-bottom:hover:before, .hvr-bubble-bottom:focus:before, .hvr-bubble-bottom:active:before{
      display: none;
    }
  }
}

.menu{
  height: 15vh;
}

li{
  text-decoration: none;
   margin-right: 10px;
  display:inline;
  height: 15vh;
}

.hvr-bubble-bottom {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  position: relative;
}
.hvr-bubble-bottom:before {
  pointer-events: none;
  position: absolute;
  z-index: -1;
  content: '';
  border-style: solid;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-property: transform;
  transition-property: transform;
  left: calc(50% - 10px);
  bottom: 0;
  border-width: 10px 10px 0 10px;
  border-color: #27AABE transparent transparent transparent;
}
.hvr-bubble-bottom:hover:before, .hvr-bubble-bottom:focus:before, .hvr-bubble-bottom:active:before {
  -webkit-transform: translateY(10px);
  transform: translateY(10px);
}

</style>