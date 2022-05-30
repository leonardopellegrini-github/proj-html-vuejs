<template>
  <div>
    <div class="grigio">
    <div class="container text-center">
      <div class="row ">
        <div class="col padd">
          <h3>PHASELLUS EGET METUS</h3>
          <h2>Forum Sections</h2>
          <div class="linearanc text-center" ></div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row justify-content-center align-items-center">
        <div :key="`icon-${index}`" v-for="(icon, index) in iconeDati"  class="box d-flex justify-content-center align-items-center text-center flex-column">
          <i :class="`${icon.i}`"></i>
          <h4>{{icon.title}}</h4>
        </div>
  
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'ForumSectionVue',
  data(){
    return{
      iconeDati:[
        {
          i: "fa-solid fa-file-lines",
          title: "News & Community"
        },
        {
          i: "fa-brands fa-apple",
          title: "Apple Forum"
        },
        {
          i: "fa-brands fa-windows",
          title: "Microsoft Forum"
        },
        {
          i: "fa-brands fa-android",
          title: "Android Forum"
        },
        {
          i: "fa-solid fa-mug-saucer",
          title: "General Discussion"
        },
        {
          i: "fa-solid fa-cubes",
          title: "Apps & Software"
        },
        {
          i: "fa-solid fa-laptop",
          title: "Gadgets & Stuff"
        },
        {
          i: "fa-solid fa-wrench",
          title: "Tutorial & Guides"
        }, 
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

.grigio{
  padding: 30px 0;
  background-color: #F2F2F2;
}

.box{
  height: 300px;
  width: 300px;
  background-color: white;
  border-top: 3px solid #27AABE;
  margin: 5px;

}

i{
  margin:30px;
  padding: 40px;
  font-size: 30px;
  color: white;
  background-color: #FC8C5E;
  border-radius: 70px;
}

h4{
  color: black;
  font-weight: 700;
}

</style>