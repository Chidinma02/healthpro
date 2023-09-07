<template>
 
 <div class="">
<!-- 
     <div class="row">
      <div class="col-md-6 col-12">
        <div class="ft mt-5">
          <h2 class="mt-5">Our love for <span class="humanity">Humanity</span> drives our <span class="passion">passion</span>  for <span class="healthcare">healthcare.</span> </h2>
        <br>

        </div>
        <p>Bridging unmet healthcare need.</p>
        <button class="btn-lg bt button-nav mar mt-4">View products</button>
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
    </div> -->
    <landingPage></landingPage>
    <featuredPro></featuredPro>
    <blogPro></blogPro>
    <discoverLanding></discoverLanding>
    <ourProject></ourProject>
    <freQuent></freQuent>
   
    <!-- <HomeFooter></HomeFooter> -->
</div>


</template>
<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import landingPage from '@/components/landingpage.vue';
import featuredPro from '@/components/featuredPro.vue'; 
import blogPro from '@/components/blogPro.vue';
import discoverLanding from '@/components/discoverLanding.vue';
import ourProject from '../components/ourProject.vue';

import freQuent from '@/components/freQuent.vue';

// import HomeFooter from '../components/HomeFooter.vue'
export default {
   name: 'HelloView',
             
  components: {
    landingPage,featuredPro,blogPro,discoverLanding,ourProject,freQuent,
    
  },
}
</script>

<style>

</style>
