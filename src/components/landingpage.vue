<template>
      <div class="container te">
        <div class="row">
      <div class="col-md-6 col-12">
        <div class="ft mt-5">
          <h2 class="mt-5 te">Our love for <span class="humanity">Humanity</span> drives our <span class="passion">passion</span>  for <span class="healthcare">healthcare.</span> </h2>
        <br>

        </div>
        <p>Bridging unmet healthcare need.</p>
        <button class="btn-lg bt button-nav mar mt-4" style="color:white">View products</button>
      </div>
      <div class="col-md-6 col-12"><img src="../assets/new.png" class="img-fluid mt-3"></div>
    
     </div>

    <div class="mt-5 ">
      <div class="row row-color mt-3 container">
       
       <div class="col-lg-5 col-12 mt-5 pt-5">
        <h5 class="what">What we do</h5>
        <p class="mt-3">We are a pharmaceutical company focused on the marketing and distribution of pharmaceutical healthcare products. But Also involved in bridging unmet healthcare needs in medical tourism, providing Diagnostic Equipment's for medical institutions and  medical training's( for Medical Personnel & Para-Medics) thereby ensuring a more knowledgeable and skillful health team.</p>
        <button class="btn-lg bt button-nav mar mt-5">Read More</button>
      </div>
       <div class="col-lg-7 col-12 mt-5">
        <img src="../assets/Group 3.png" class="img-fluid">
       </div>
     </div>
    </div>
      </div>
</template>

<script>
export default {
   name:'LandingPage'
}
</script>

<style>
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
.what{
  color:#D41420;
}
.row-color{
  background-color:#F2F8F7;
}
.button-nav{
  background-color: #258576 !important;
  width:135px;
  height:42px;
  border: 0px;
  border-radius:34px;
  color:white !important;
  font-size: 16px !important;
}
.ft{

  display: flex;
  height:50h;
  align-items: center; /* Vertically center content */


}
.healthcare{
  color:#258576;
}
.passion{
  color:#BE0F44;
}
.humanity{
color:#FCB912 !important;
}
h2{
  font-size: 50px !important;
  font-family: 'Custom' !important;

}



</style>