<template>
  <div class="main-div">
    <div class="container di">
      <div class="row container">
      <div class="col-6 di">
        <div>
            <h1 class="h1-dis te">Discover a world of healthcare solutions at your fingertips.</h1>
        <p>Healthline is here to support you on your journey to better health.</p>
        <button class="btn-lg bt button-nav mar mt-4 text-center">Read More</button>
        </div>
      
      </div>
      <div class="col-6 di">
        <img src="../assets/newes.png" class="img-fluid">
      </div>
    </div>
    </div>
  
  </div>
</template>

<script>
export default {
    name:'discoverLanding'
}
</script>

<style>
.h1-dis{
  font-family: 'custom-font';
  color:#18564C;
  font-weight:bold;
}
.di{

      display: flex;
      justify-content: center;
      align-items: center;
      /* height: 100vh; Adjust this value as needed */
    
}
.main-div{
     background-image: url("../assets/new\ \(2\).png");
    height:90%;
    background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover; 
 
  padding-top:10px !important;
  padding-bottom:10px !important;
  margin:0 !important
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