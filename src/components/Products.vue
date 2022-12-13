<template>
<h1>Products</h1>
<h3>Here are some of our best selling products!</h3>

<div class="container">
    <div style="display: grid; grid-template-columns: repeat(4, 1fr)">
          <div class="card" v-for="item in arr" :key="item" style="width: 18rem;height:35rem; grid-column:span 1;">
            <img :src="item.image" class="card-img-top"  alt="...">
            <div class="card-body">
              <h5 class="card-title">{{item.product}}</h5>
              <p class="card-text">{{item.Price}}</p>
              <button class="btn btn-primary" v-on:click="showAlert">  Add to Cart</button>
            </div>
          </div>
    </div>
</div>
</template>
<script>


export default {
    name: 'Products',
    
    data() {
        return {
     arr : [
    {
        product: 'Oreos',
        image:"https://i.postimg.cc/GtZTRxc7/product1.png",
        Price: 'R10'    
    },
    {
        product: 'Jambos',
        image:"https://i.postimg.cc/WzrghHfL/product2.webp",
        Price: 'R10'    
    },
    {
        product: 'Toppers',
        image:"https://i.postimg.cc/Z5YvSnZh/product3.png",
        Price: 'R10'    
    },
    {
        product: 'Romany Creams',
        image:"https://i.postimg.cc/JhcFBpvX/product4.png",
        Price: 'R10'    
    }
] 
    }
    }
    
}

function showAlert() {
    alert("Added to Cart")
}

</script>
<style>
    
</style>