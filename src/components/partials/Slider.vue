<template>
   <div class="jumbotron">

      <div class="container-jumbo">

         <div class="slider">

            <div class="slide-track">

               <div class="slide" id="illustrator">
                  <img src="../../../dist/assets/img/Illustrator.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/Laravel.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/mysql.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/photoshop.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/php.svg" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/vsc.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/logo_html_css.png" alt="">
               </div>
               <div class="slide" id="js">
                  <img src="../../../dist/assets/img/logo_js.png" alt="">
               </div>
               <div class="slide" id="github">
                  <img src="../../../dist/assets/img/github.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../../dist/assets/img/vue.png" alt="">
               </div>

               <!-- doppioni -->

               <div class="slide" id="illustrator">
                  <img src="../../dist/assets/img/Illustrator.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/Laravel.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/mysql.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/photoshop.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/php.svg" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/vsc.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/logo_html_css.png" alt="">
               </div>
               <div class="slide" id="js">
                  <img src="../../dist/assets/img/logo_js.png" alt="">
               </div>
               <div class="slide" id="github">
                  <img src="../../dist/assets/img/github.png" alt="">
               </div>
               <div class="slide">
                  <img src="../../dist/assets/img/vue.png" alt="">
               </div>

            </div>

         </div>
         
      </div>
   </div>

   <div class="main">
      Questo è il main
   </div>

</template>

<script>

export default {
   name: 'HomePageView',
   components:{
      
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