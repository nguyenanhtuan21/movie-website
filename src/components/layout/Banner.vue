<template>
  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="../../assets/img/Extraction_2020_film.jpg" alt="First slide" height="400px">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../../assets/img/Quý-Ông-Sở-Thú-Mr.-Zoo-The-Missing-VIP-2020-2-750x433.jpg" alt="Second slide" height="400px">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../../assets/img/sat-thu-vo-cung-cuc.jpg" alt="Third slide" height="400px">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</template>

<script>
import $ from 'jquery'
import 'bootstrap/dist/js/bootstrap.min.js'
export default {
    name: 'Banner',
    data(){
        return {

        }
    },
    methods: {
        onChageSlide(){
            document.querySelector(".carousel").carousel('next')
        }
    },
   
};
</script>
<style scoped lang="scss">

</style>
