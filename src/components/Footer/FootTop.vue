<template>
  <div>
    <div class="footer">
    <div class="container text-center text-md-start mt-5">
   
      <div class="row mt-3">
        <!-- COLONNA 1 -->
        <div class=" col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
          <h6 class="text-uppercase fw-bold mb-4">
            AVADA TECH FORUM
          </h6>
          <p>
            Sed semper, nisl id feugiat eleifend, erat est digssim felis, quis auctor elit enim nec ante. Cras et nibh risus. Pellentesque non mi sit amet mi intermentum.
          </p>
        </div>

        <!-- COLONNA 2 -->
        <div class="footcol col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
  
          <h6 class="text-uppercase fw-bold mb-4">
            POPULAR TOPICS
          </h6>
          <p><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Vivamus pellenteque, felis quis varius
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Donec ornare pretium eget scelisque justo
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
        </div>

        <!-- COLONNA 3 -->
        <div class="footcol col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
          
          <h6 class="text-uppercase fw-bold mb-4" >
            RECENT TOPICS
          </h6>
          <p><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Vivamus pellenteque, felis quis varius
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Donec ornare pretium eget scelisque justo
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
        </div>

        <!-- COLONNA 4 -->
        <div class="footcol col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
          <h6 class="text-uppercase fw-bold mb-4">
            LATEST REPLIES
          </h6>
          <p ><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Vivamus pellenteque, felis quis varius
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Donec ornare pretium eget scelisque justo
          </p>
          <p><i class="fa-solid fa-angle-right"></i>
            Morbi vitae dui euismod vulputate sollicitudin
          </p>
        </div>
      </div>
     </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FootTopVue'
}
</script>

<style lang="scss" scoped>

.footcol{
  p{
  &:before{
    position: absolute;
    font-weight: 300;
    font-family: "Font Awesome 6 Free"; 
  
    margin-left: -12px;
  }
  }

}



</style>