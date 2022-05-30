<template>
  <div>
    <!--PRIMA PARTE-->
    <div class="container">
      <div class="card-group">
      <div class="col-4 p-2 carta" :key="`articolo-${indice}`" :class="{'none' : articolo.feature === true}" v-for="(articolo, indice) in articoli">
       <img :src="require(`@/assets/img/post_feat_img_`+ articolo.immagine+`-700x441.jpg`)" class="card-img-top"  alt="Card image cap">
       <div  class="card-body">
         <h4>{{articolo.titolo}}</h4>
         <p>{{articolo.data}} | {{articolo.commenti}}</p>
         <p class="card-text">{{articolo.testo}}</p>
       </div>
     </div>
     <div class="col-12 featured d-flex justify-content-around flex-column">
        <h3>FEATURED ARTICLE</h3>
        <h1>Cras Malesuada Et Orci Eget Pharetra</h1>
        <p>In quis lectus sed leo elementum faucibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.</p>
        <a href="#">READ MORE <i class="fas fa-arrow-right"></i></a>
     </div>     
    </div>
    </div>

    <!--SECONDA PARTE-->
    <div class="container secondapart">
      <div class="row">
        <div class="col-8 featured">
        <h3>FEATURED ARTICLE</h3>
        <h1>Cras Malesuada Et Orci Eget Pharetra</h1>
        <p>In quis lectus sed leo elementum faucibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.</p>
        <a href="#">READ MORE <i class="fas fa-arrow-right"></i></a>
      </div>
      <div class="col">
        <h2>Tutorial & guides</h2>
        <div class="linearanc" ></div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LastestPostVue',
   data(){
    return{
      articoli:[
        {
          immagine: "25",
          titolo: "Morbi vitae dui euismod vulputate sollicitudin",
          data: "October 11th, 2015",
          commenti: "2 Comments",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
        },
        {
          immagine: "24",
          titolo: "Vivamus pellenteque, felis quis varius",
          data: "October 11th, 2015",
          commenti: "Comments Off",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
          },
        {
          immagine: "23",
          titolo: "Donec ornare pretium eget scelisque justo",
          data: "October 11th, 2015",
          commenti: "Comments Off",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
        },
        {
          immagine: "22",
          titolo: "Cras Malesuada Et Orci Eget Pharetra",
          data: "October 11th, 2015",
          commenti: "",
          testo: "In quis lectus sed leo elementum faucibus in dapibus dictum. Nullamolestie tortor nec lectus venenatis, sed blandit dui, dolor at bibendum sadips ets ipsums dolores ficilis uns leo lectus.",
          feature: true,
        },
        {
          immagine: "21",
          titolo: "Fusce sollicitudin nunc sed placerat varius",
          data: "October 11th, 2015",
          commenti: "Comments Off",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
        },
        {
          immagine: "20",
          titolo: "Donec facilis sodales leo sit amet laoreet",
          data: "October 11th, 2015",
          commenti: "Comments Off",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
        },
        {
          immagine: "25",
          titolo: "Donec facilis sodales leo sit amet laoreet",
          data: "October 11th, 2015",
          commenti: "2 Comments",
          testo: "Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl",
          feature: false,
        },
      ]
    }
  }
}
</script>

<style lang="scss">

.none{
  display: none;
}

.block{
  display: block;
}

.featured{
  background-image: url(@/assets/img/featured_article_1_bg.jpg);
  background-size: cover;
  height: 450px;
  color: white;
  padding: 40px;
  h3{
    color: white;
  }
  a{
  padding:20px;
  width: 15%;
  background-color: black;
  font-size: 20px;
  text-decoration: none;
  color: white;
  font-weight: 600;
  }
  p{
   font-size: 15px; 
  }
}

.secondapart{
  padding: 30px 0px;
}

.carta{
  img{
    transition: all 0.5s ease;
  }
  img:hover{
   border-radius: 20px;
   filter: saturate(200%);
   filter: sepia(30%);
  }
  
}



</style>