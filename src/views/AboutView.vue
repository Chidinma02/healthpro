<template>
  <div class="about">
    <!-- <h1>This is an about page</h1> -->
    <AboutFirst></AboutFirst>
    <AboutSecond></AboutSecond>
    <ThirdSecond></ThirdSecond>
    <AboutThird></AboutThird>
    <ourproject></ourproject>
  </div>
</template>
<script>
import AboutFirst from '@/components/AboutFirst.vue';
import AboutSecond from '@/components/AboutSecond.vue';
import ThirdSecond from '@/components/ThirdSecond.vue';
import ourproject from '@/components/ourProject.vue';
import AboutThird from '@/components/AboutThird.vue';
export default {
 name:'AboutView',

 components:{
      AboutFirst,AboutSecond,ThirdSecond,ourproject,AboutThird
 }
}
</script>