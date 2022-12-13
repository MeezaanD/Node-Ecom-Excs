<template>
  <NavBar/>
  <body>
    <!-- <h1>THE R10 SHOP</h1> -->
    <img class="img" src="https://i.postimg.cc/J4yJQBFn/biscuits.jpg"  alt="">
  </body>
   <Footer/>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  components: {
  HelloWorld, NavBar, Footer
  }
}
</script>

<style>
.img {
  width: 98vw;
  height: 87vh;
  padding: 5px;
}
</style>