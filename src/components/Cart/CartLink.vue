<template>
    <div>
        <secondbar></secondbar>
        <div class="container ca  mb-5">
       <div class="row ">
            <div class="col-md-4 offset-md-4 col-12 text-center mt-5 mb-5">
                <img src="../../assets/ShoppingCart.png" class="img-fluid op">
                <p>Your Cart</p>
                <p>Browse our categories and discover our best deals!</p>
                <button class="se">Start Shopping</button>
            </div>

            <div class="row">
                <div class="col-4" v-for="cart in cartItems" :key="cart.id">
                    <img :src="cart.image"  class="img-fluid">
                </div>
                
            </div>
        <ul>
            <li v-for="cart in cartItems" :key="cart.id">{{ cart.name }}</li>

        </ul>
       </div>
    </div>
    </div>
    
</template>

<script>
import secondbar from '../secondBar.vue'


export default {
name:'CartLink',
data(){
    return{
        cartItems:JSON.parse(sessionStorage.getItem("cart"))
    }
},
components:{
    secondbar   
},
methods:{

},
mounted:{
    
}
}
</script>

<style>
.op{
    width:40.83px;
    height:40.83px;
}
.ca{
    border:1px solid #E0E0E0;
    border-radius:10px;
}
.se{
    padding-top:5px;
    padding-bottom:5px;
    padding-left:30px;
    padding-right:30px;
    background-color:black;
    color:white;
    border:none;
    border-radius:15px;
}
</style>