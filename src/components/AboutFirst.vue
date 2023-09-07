<template>
     <div class="main">
        <div class="row">
            <div class="col-12  cen">
                <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="../assets/Frame 112.png" alt="First slide">
      <div class="carousel-caption ">
        <h2 class="weoff  d-none d-md-block">We offer a wide range of<br> products and services,</h2>
    <p class="weoff  d-none d-md-block">medical training , diagnostic equipment,updates on medical breakthrough studies and medical conferences</p>
   <p class="d-block d-md-none">We offer a wide range of products and services,medical training , diagnostic equipment,updates on medical breakthrough studies</p>
  </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../assets/Frame 112.png" alt="Second slide">
      <div class="carousel-caption ">
    <h2 class="weoff d-none d-lg-block d-xl-none">We offer a wide range of<br> products and services.</h2>
    <p>medical training , diagnostic equipment,updates on medical breakthrough studies and medical conferences</p>
  </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../assets/Frame 112.png" alt="Third slide">
        <div class="carousel-caption">
    <h2 class="weoff d-none d-lg-block d-xl-none">We offer a wide range of<br> products and services.</h2>
    <p>medical training , diagnostic equipment,updates on medical breakthrough studies and medical conferences</p>
  </div>
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
            </div>
        </div>
      
     </div>
</template>

<script>
export default {

}
</script>

<style>
.weoff{
    font-weight: bolder;
}
.main{
    overflow: hidden;
} .parent {
      display: flex !important;
      justify-content: center !important;
      align-items: center !important;
      /* height: 100vh; Adjust this value as needed */
    }
    .carousel-caption{
        top: 50%;
transform: translateY(-50%);
bottom: initial;
    }

</style>