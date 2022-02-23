<template>
   <div id="header">

      <div class="container-home-page">

         <div class="logo">
            <h2>
               Junior Web Developer
            </h2>
         </div>

         <div class="navigation">
            <a href="#">
               I miei lavori
            </a>
            <a href="#">
               Contattami
            </a>

         </div>

      </div>

   </div> 
</template>

<script>
export default {

}

</script>

<style>

#header {
   background-color: black;
   color: white;
   font-size: 20px;
   top: 0;
   left: 0;
   line-height: 80px;
   height: 80px;
   width: 100vw;
   transition: 0.2s;
}

.container-home-page{
   width: 80%;
   margin: 0 auto;
   display: flex;
   justify-content: space-around;
   align-items: center;
   border-bottom: 1px solid rgb(255, 154, 1);
   z-index: 99;
}

.container-home-page .navigation{
   width: 30%;
   display: flex;
   justify-content: space-around;
}

.navigation a{
   color: white;
   font-size: 17px;
   text-transform: uppercase;
   text-decoration: none;
}

.navigation a:hover{
   text-decoration: underline;
   color: rgb(255, 154, 1);
   transition: all 0.3s;
}




</style>