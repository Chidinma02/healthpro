<template>
   <div>
    <div class="container">
    <div class="navb">
  <b-navbar toggleable="lg">
    <b-navbar-brand href="#"><img src="../assets/Frame 8.png" class="img-class"></b-navbar-brand>

    <b-navbar-toggle  type="light" variant="light" target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="mx-auto">
        <b-nav-item href="#" class="ma ml-5" ><router-link to="/" class="rou">Home</router-link></b-nav-item>
        <b-nav-item href="# " class="ml-5  mar ma ">
           <router-link to="/about" class="rou">About Us</router-link></b-nav-item>
        <b-nav-item-dropdown text="Products" right  class="ml-5 mar">
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="#"  class="ml-5  mar ma">Blog</b-nav-item>
       
       
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#"><button class="btn-lg bt button-nav mar">Contact Us</button></b-nav-item>
        <b-nav-item href="#" class="mt-2 ma"><img src="../assets/ShoppingCart.png" class="imgf ml-5"></b-nav-item>
      

       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>


    
    
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
  font-family:"CustomFont"
}
/* @font-face {
  font-family: 'CustomFont'; /* Provide a name for your font */
  /* src: url('../assets/font/Inter-VariableFont_slnt\,wght.ttf') format('ttf');
     
  font-weight: normal;
  font-style: normal;
} */
.imgf{
  width:32px;
  height: 32px;
  
}
*{
  color:black !important;
  font-weight:100 !important;
  font-size: 16px !important;
}

b-navbar-nav{
  color:black !important;
}
.ma{
 
  font-size: 18px;
  color:blue;
}
.navb{
  color:blue !important
}
.navbar-nav{

}
.img-class{
  width: 183.58px;
      height: 19.16px;
      /* border: 10px solid blue; */
}
.ml-auto, .mx-auto {
    margin-left: auto!important;
}
*{
  background-color:white;
  font-family: 'CustomFont';
}
.button-nav{
  background-color: #258576;
  width:135px;
  height:42px;
  border: 0px;
  border-radius:34px;
  color:white !important;
  font-size: 16px !important;
}
.mar{
  margin-left:20px;
}
.rou{
  text-decoration: none !important;
}
</style>
