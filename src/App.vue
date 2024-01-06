<template>
  <div id="app">
   <HelloWorld v-if="!$route.meta.hideNavigation"></HelloWorld>
    <router-view/>
    <HomeFooter v-if="!$route.meta.hideNavigation"></HomeFooter>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue';
import HomeFooter from './components/HomeFooter.vue';
export default {
  
   components: {
   HelloWorld, HomeFooter
  }
}
</script>
<style>

 
*{
  padding: 0px ;
  MARGIN:0px ;
  
  font-family: facee;

}
@font-face {
  font-family: face;
  src: url(../src/assets/Millik.otf);
}
@font-face {
  font-family: facee;
  src: url(../src/assets/Inter-Regular.otf);
}

#app {

  
  
}
.head{
 /* ? margin:0px !important; */
  /* padding:0px !important; */
}


</style>
