<template>

   <Header />

   <Slider />

   <div class="main">

      <div class="container">

         <div class="myself">
            prova
         </div>

         <div class="nerd-image">
            prova
         </div>

      </div>


   </div>

</template>

<script>
import Header from '../components/partials/Header.vue'
import Slider from '../components/partials/Slider.vue'

export default {
   name: 'HomePageView',
   components:{
      Header,
      Slider
   }
}

</script>

<style scoped>

.jumbotron{
   width: 100vw;
   overflow: hidden;
   background-color: black;
   /* padding-top: 30px; */
}

.container{
   width: 85%;
   margin: 35px auto;
}

.main .container{
   display: flex;
   justify-content: space-between;
   align-self: center;
}
.main{
   background-color: blueviolet;
   padding: 50px;
}

.myself,
.nerd-image{
   width: 45%;
}

.myself{
   background-color: burlywood;
}

.nerd-image{
   background-color:yellowgreen;
}


</style>