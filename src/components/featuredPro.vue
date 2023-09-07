<template>
    
    <div>
     
      <div class="container">
        <h3 class="mt-5 fea te">Featured Products</h3>
      </div>
        <div id="carouselExampleControls" class="carousel carousel-dark slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <div class="card-wrapper container-sm d-flex  justify-content-around">
      <div class="card  " style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
  </div>
</div><div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
  </div>
        </div>
        <div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
  </div>
</div>
</div>
    </div>
    <div class="carousel-item">
      <div class="card-wrapper container-sm d-flex   justify-content-around">
      <div class="card  " style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top img-fluid" alt="...">
  <div class="card-body">
    <!-- <h5 class="card-title">Card title</h5> -->
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
  </div>
</div><div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
    
  </div>
        </div>
        <div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">#1200 Paracetamol</h5>
    <p>pain relief</p>
    
    
  </div>
</div>
    </div>
    </div>
    <div class="carousel-item">
      <div class="card-wrapper container-sm d-flex  justify-content-around">
      <div class="card " style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    
  </div>
</div>
        <div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    
  </div>
        </div>
        <div class="card" style="width: 18rem;">
  <img src="../assets/para.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    
  </div>
</div>
    </div>
  </div>
 
</div>
    
<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>

</div>
    </div>
    
   

</template>

<script>
export default {
  
    name: 'featuredPro',
    
}

</script>

<style>
/* @font-face {
  font-family: 'Custom'; /* Provide a name for your font */
  /* src: url('../assets/font/Millik\ Regular.otf') format('otf');
     
  font-weight: normal;
  font-style: normal;
} */ 
 .fea{
	font-family:'Custom';
  color:#258576;
 }.card{
    padding:0;
    
  }
  .card-wrapper{
    
  }
  .card{
    border:none !important;
  }
  @font-face {
  font-family: 'milki'; /* Provide a name for your font */
  /* src: url('./assets/font/Inter-Regular.otf') format('otf'); */
  src: url('../assets/font/Millik\ Regular.otf')format('otf');
     
  font-weight:normal;
  font-style:normal;
}
 .te{
	font-family:'milki' !important;
   
  } 
</style>