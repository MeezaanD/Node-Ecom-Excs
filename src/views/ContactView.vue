<template>
  <NavBar/>
  <Contact/> 
   <Footer/>
   
</template>
<script>
import Contact from "../components/ContactForm.vue"
import NavBar from "../components/NavBar.vue"
import Footer from "../components/Footer.vue"
 
 export default {
     components:{
        NavBar, Contact, Footer
     }
 }
</script>
<style>
    
</style>