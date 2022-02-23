<template>

   <Header />

   <Slider />

   <div class="main">
      Questo è il main
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

<style>

.jumbotron{
   width: 100vw;
   overflow: hidden;
   background-color: black;
   /* padding-top: 30px; */
}

.container-jumbo{
   width: 80%;
   margin: 35px auto;
}

/* slider */

.slider{
   height: 100px;
   margin:auto;
   position: relative;
   width: 100%;
   display: grid;
   place-items: center;
   overflow: hidden;
}

.slide-track{
   display: flex;
   width: calc(150px * 20);
   animation: scroll 100s linear infinite;
}

.slide-track:hover{
   animation-play-state: paused;
}

@keyframes scroll {
   0%{
      transform: translateX(0);
   }
   100%{
      transform: translateX(calc(-150px * 10));
   }
}

.slide{
   height: 90px;
   width: 130px;
   display:flex;
   align-content: center;
   padding: 15px;
}

img{
   width: 100%;
}

#github img,
#illustrator img,
#js img{
   width: 75%;
   margin: 0 auto;
}

/* fine slider */

.main{
   height: 1000px;
   background-color: blueviolet;
}

</style>