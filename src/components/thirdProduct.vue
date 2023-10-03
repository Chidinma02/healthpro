<template>
  <div>
    
    <div>
    <div class="container">
    <div class="navb">
  <b-navbar toggleable="lg">
    <!-- <b-navbar-brand href="#"><img src="../assets/Frame 8.png" class="img-class"></b-navbar-brand> -->

    <b-navbar-toggle  type="light" variant="light" target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="">
        <b-nav-item href="#" class="ma ml-5 pharnav" ><router-link to="/" class="rou pharnav">Pharmacy</router-link></b-nav-item>
        <b-nav-item href="# " class="ml-5  mar ma ">
           <router-link to="/about" class="rou pharnav">Vitamins & Supplements</router-link></b-nav-item>
       
           <b-nav-item href="# " class="ml-5  mar ma ">
           <router-link to="/about" class="rou pharnav">Sexual wellbeing</router-link></b-nav-item>
           <b-nav-item href="# " class="ml-5  mar ma ">
           <router-link to="/about" class="rou pharnav">Skincare</router-link></b-nav-item>
       
        <!-- <b-nav-item href="#"  class="ml-5  mar ma">Blog</b-nav-item> -->
       
       
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ms-auto">
        <b-form-input size="sm" class="mr-sm-2" placeholder="Search" fr></b-form-input>
        <!-- <input type="text" style="width: 1000px;"> -->
       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
 <h3 class="mt-5 pr">Products</h3>
 <div class="row">
    <div class="col-12 col-md-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Anti Infectives</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Anti Infectives</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Anti Infectives</p>
    </div>
 </div>

 <div class="row">
    <div class="col-12 col-md-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Blood Tonics and Ani-aneamics</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Multivitamins/Antioxidants</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Dental range</p>
    </div>
 </div>

 <div class="row">
    <div class="col-12 col-md-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Antiseptics</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Anti Infectives</p>
    </div>
    <div class="col-4">
      <img src="../assets/Frame 83-min.png" class="img-fluid">
      <p>Anti Infectives</p>
    </div>
 </div>
 <div>
  <nav aria-label="Page navigation example  mt-5">
 
 <ul class="pagination justify-content-center">
 <li class="page-item"><a class="page-link" href="#">
   <router-link to="/about" class="pe">Previous</router-link></a></li>
 <li class="page-item"><a class="page-link pe" href="#">1</a></li>
 <li class="page-item"><a class="page-link pe" href="#">2</a></li>
 <li class="page-item"><a class="page-link pe" href="#">3</a></li>
 <li class="page-item"><a class="page-link pe" href="#">Next</a></li>
</ul>


</nav>
 </div>



    
    
  </div>
  </div>


  
  </div>
</template>

<script>

export default {

name:'thirdProducts',
data(){
  return {
      currentPage: 1,
      perPage: 6, // Number of images per page
      images: [
        { src: '../assets/f1-min.png' },
        { src: '../assets/f1-min.png' },
        // Add more image objects here
      ],
    };
},
computed:{
  paginatedImages() {
      const startIndex = (this.currentPage - 1) * this.perPage;
      const endIndex = startIndex + this.perPage;
      return this.images.slice(startIndex, endIndex);
    },
}
}
</script>

<style>
.pe{
  color:black !important;
  text-decoration: none !important;
}
.pharnav{
  color:black;
  text-decoration:none;
}

input{
  width:400px !important;
  border-radius:120px !important;
}
.mu{
  display: flex;
  justify-content: center; 
  align-items: center; 
  
}
.pag{
  display: flex;
    justify-content: center; 
    align-items: center; 
    min-height: 100vh; 
}
</style>