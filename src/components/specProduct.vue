<template>
  <div>
    <secondBar></secondBar>
    <div class="container mb-5">
        
      
        <h3 class="pr mt-3">Products</h3>
        <p>{{ cart.length }} cccccccc</p>
      

        <div class="row mt-3">
            <div class ="col-md-3 col-12"  v-for="post in this.posts " :key="post.id">
                <div class>
                      <img src="../assets/chd.png" class="container-fluid we" > 
                    <!-- <img :src="post.image"  class="img-fluid"> -->
                    <div class="row">
                        <div class="col-7">
                          <p class="myh">{{post.drug_name
 }}</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-5">
                            <button class="buy" @click="addToCart(post)">Add to cart</button>
                           <!-- <p class="mh"> ₦ 2,800</p> -->
                        </div>

                    </div>
                </div>
            </div>
            <!-- <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-3">
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/chd.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-3 ">
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class ="col-md-3 col-12">
                <div class>
                    <img src="../assets/para.png" class="container-fluid we" >
                    <div class="row">
                        <div class="col-8">
                          <p class="myh">MyHep DVIR</p>
                          <p class="ni">Anti-removal</p>
                          <p  class="av in"><span><img src="../assets/Ellipse 43.png" class="im1" ></span>Available for delivery</p>
                          <p  class="av "><span><img src="../assets/Ellipse 43.png" class=" im1"  ></span>In stock</p>
                        </div>
                        <div class="col-4">
                           <p class="mh"> ₦ 2,800</p>
                        </div>
                    </div>
                </div>
            </div>
        </div> -->
        
    </div>
  </div>
  </div>
</template>

<script>
import axios from 'axios'
import secondBar from './secondBar.vue';


export default {
  name:'specProduct',
  components:{
  secondBar,
//   cartview

},
data(){
      return{
        cart:[],
        posts:[],
        baseUrl: process.env.MAIN_API ? process.env.MAIN_API : "",
      }
    },
    
    methods: {
      updateProfile () {
        alert('Your data: ' + JSON.stringify(this.user))
      },
      
      addToCart(post) {
      const cartItem = this.cart.find(item => item.id === post.id);
    //   alert(cartItem)
      if (cartItem) {
        cartItem.quantity += 1;
      } else {
        this.cart.push({
          id: post.id,
          name: post.drug_name,
          price: post.price,
          image:post.image,
          quantity: 1,
        });
      }
      console.log(this.cart);
      sessionStorage.setItem("cart", JSON.stringify(this.cart));
    }
    
    //  addToCart(product){
    //   this.cart.push(product);
    //     console.log(this.cart);
    //    sessionStorage.setItem(this.cart.id,this.cart);
    //   }

    // addToCart(product) {
    //   this.cart.push(product);
    //   console.log(this.cart);
    //   // Emit an event with the updated cart data
    //   this.$emit('cart-updated', this.cart);
    // },
    },
   mounted(){
   axios.get('https://prosperc40.pythonanywhere.com/products',{
      headers: {
    'Authorization': 'Token ' + '6124bc0794931a48a4665935619ee039bb7be277'
  }}
      )
  .then(response => {
    console.log(response);
    this.posts=response.data

    console.log(this.posts)
    // Now check the structure of the response and ensure it has a 'protocol' property.
  })
  .catch(error => {
    console.error('Error fetching data:', error);
  })
    
    }
  
}
</script>

<style>
.buy{
  background-color:#258576;
  border:0;
  font-size:13px;
  padding-left:10px;
  padding-right:10px;
  color:white;
  border-radius:20px;
}
.we{
    width:"297px";
    width:"295px";
}
.myh{
    font-size:16px !important;
    font-weight:500 !important; 
    margin-bottom: 0; 
  padding-bottom: 0; 
  line-height: 2;
}
.mh{
    font-size:16px !important;
    font-weight:700 !important; 
}
.ni{
    font-size:12px !important;
    color:#535353 !important;
}
.av{
    font-size:12px !important;
    
}
.in{
    margin-bottom: 0; 
  padding-bottom: 0;
  line-height: 1;
}
.im1{
    width:12px;
    height:12px;
    margin-right:10px;
    
}
.pr{
    color:#258576
}
</style>