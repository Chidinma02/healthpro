<template>
    <div>
        <secondbar></secondbar>
        <div class="container">

        <h4 class="mt-3">Pharmacy Cart</h4>
      <div class="row">
        <div class="col-md-7 col-12 mr">
            <div class="row container">
                <div class="col-md-2 mt-4 col-12">
                    <img src="../../assets/para.png" class="ts" >
                </div>
                <div class="col-md-9 col-12">
                    <h4 class="mt-3 mk">Emeceph</h4>
                    <p class="cef">Ceftriaxone for injection USP1.0gIM/IV Use</p>
                    <p class=""><span class="io">Presentation</span> :<span class="pre">1 Vail</span></p>
                    <p class="pre">Quantity</p>
                    <p class=""><span ><button class="minus">-</button></span><span class="forty">40</span><span><button class="minus">+</button></span></p>
                </div>
                <div class="col-md-1 col-12 lo">
                    <div class="lo"><p class="lo">X</p> 
                    <p class="lo">₦2,800.00</p></div></div>
                    
            </div>
        </div>
        <div class="col-md-1 col-12"></div>
        <div class="col-md-4 col-12  fd">
        <div class="row container ">
            <div class="col-6 ">
                <h5>Order Summary </h5>
                <P>No of items</P>
                <p>Total</p>
            </div>
            <div class="col-6 lo">
                
                <P class="mt-4">2</P>
                <p>2000</p>
            </div>
            <button class="fh pt-1 pb-1">Place Order</button>
        </div>
        </div>
      </div>
      <div class="row mt-4 mb-5">
        <div class="col-md-7 col-12 mr">
            <div class="row container">
                <div class="col-md-2 mt-4 col-12">
                    <img src="../../assets/para.png" class="ts" >
                </div>
                <div class="col-md-9 col-12">
                    <h4 class="mt-3 mk">Emeceph</h4>
                    <p class="cef">Ceftriaxone for injection USP1.0gIM/IV Use</p>
                    <p class=""><span class="io">Presentation</span> :<span class="pre">1 Vail</span></p>
                    <p class="pre">Quantity</p>
                    <p class=""><span ><button class="minus">-</button></span><span class="forty">40</span><span><button class="minus">+</button></span></p>
                </div>
                <div class="col-md-1 col-12 lo">
                    <div class="lo"><p class="lo">X</p> 
                    <p class="lo">₦2,800.00</p></div></div>
                    
            </div>
        </div>
        <div class="col-md-1 col-12 ">
        
    </div>
        <div class="col-md-4 col-12 ">
        
        </div>
      </div>
    </div>
    </div>
 
</template>

<script>
import secondbar from '../secondBar.vue'

export default {
name:'CartChoose',
components:{
    secondbar
}
}
</script>

<style>
.fh{
    background-color: #258576;
    color:white;
    border:none;
    border-radius:8px;
}
.fd{
    border:1px solid #E0E0E0;
    border-radius:10px;
    
}
.lo{
    text-align: right;
    float: right;
}
.mr{
    border:1px solid #E0E0E0;
    border-radius:10px;
}
.ts{
    width:62px;
height: 62px;
}
.mk{
    font-weight:bold;
}
.cef{
    margin-bottom: 0; 
  padding-bottom: 0; 
  line-height: 1.2;
  color:#343434;
  font-size: 16px;
  
}
.pre{
    margin-top:-20px;
  
  color:#343434;
  font-size: 13px;
  
}
.io{
 color:#525252 !important;font-size: 13px;
 
 margin-bottom: 0; 
  padding-bottom: 0; 
  line-height: 1.2;
  font-size: 13px;
  margin-top:-10px
}
</style>