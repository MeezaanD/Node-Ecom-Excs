<template>
    <NavBar/>
   <Products/>
   <Footer/>
</template>
<script>
import Products from "../components/Products.vue";
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue" ;

export default {
    components: {
        Products, NavBar, Footer
    } 
}
</script>
<style>
    
</style>