<template>
 

  <div class="container can mt-">
    <div class="row">
        <div class="col-12 so">
          <h3 class="de">Frequently asked Questions and Answers</h3>
          <p>What is on your mind about us</p>
        </div>
    </div>
  <div class="accordion" id="accordionExample">
    <div class="card">
      <div class="card-header " id="headingOne" data-toggle="collapse" data-target="#collapseOne">
        <span class="icon " ><i class="fas fa-chevron-down"></i></span>
       <span class="ml-3">How do i get my Products delivered to my location.</span> 
      </div>
      <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#accordionExample">
        <div class="card-body ">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam facilis dicta sit dolorum quisquam esse necessitatibus voluptate quidem at non placeat, ipsam unde officiis. Asperiores veniam tempora labore ab id.
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-header" id="headingTwo" data-toggle="collapse" data-target="#collapseTwo">
        <span class="icon"><i class="fas fa-chevron-down"></i></span>
        <span class="ml-3">Are there extra charges for product delivery.</span> 
      </div>
      <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
        <div class="card-body">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut commodi ea asperiores voluptates sequi consectetur temporibus, quis doloribus nobis provident blanditiis, non tempore beatae. Aliquid vel laudantium aut sunt ipsum.
        </div>
      </div>
    </div>
    <!-- Add more accordion items as needed -->
  </div>

  <div class="subscribe">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-8"> <h5>Subscribe to our News Letter and get exclusive updates</h5><h5> when we post a new blog.</h5>
        </div>
        <div class="col-12 col-md-4 bu">   <button class="btn-lg bt button-nav mar mt-4 text-center">Subscribe</button></div>
      </div>
    </div>
   
  </div>
</div>



</template>

<script>
export default {
 name:'freQuent'
}
</script>

<style>
.de{
  color:#18564C;
    font-family: 'Customfont';
    font-weight:bold;
}
.so{
  text-align: center;
}

.bu{
  display: flex;
      justify-content: center;
      align-items: center;
}
.button-nav{
  background-color: white;
  width:135px;
  height:42px;
  border: 0px;
  border-radius:34px;
  color:white !important;
  font-size: 16px !important;
}
.subscribe{
  background-color:#18564C;
  margin-top:200px;
  color:white;
  /* padding-top:20px;
  padding-top:20px; */
  border-radius:10px;
  display: flex;
      justify-content: center;
      align-items: center;
      height: 42%; 
      margin-bottom: 100px;
      padding-left: 20px;
      padding-right:20px;
      padding-top:40px;
      padding-bottom:40px;
}
template{
  background-color:white !important;
}
.can{
  background-color:white !important;
}
.accordion{
 
}
 .accordion .card-header {
      cursor: pointer;
      position: relative;
    }
    .accordion .card-header .icon {
      position: absolute;
      left: 10px;
      top: 50%;
      transform: translateY(-50%);
    }
    .accordion .card-header .icon::before {
      font-size: 1.2em;
    }
    .collapsed .icon::before {
      content: '+';
    }
    .icon::before {
      content: '+';
    }
</style>