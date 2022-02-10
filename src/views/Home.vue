<template>
  <div class="home">
   <!--<img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />--> 
    <Carousel/>
    <Cartes/>
    <!-- <Randonnee/> -->
  </div>
</template>

<script>
// @ is an alias to /src
/*import HelloWorld from "@/components/HelloWorld.vue";*/
import Carousel from "@/components/Carousel.vue";
import Cartes from "@/components/Cartes.vue";
//import Randonnee from "@/components/Randonnee.vue";


export default {
  name: "Home",
  components: {
   /* HelloWorld,*/Carousel,Cartes,/* Randonnee */
  },
};
</script>
