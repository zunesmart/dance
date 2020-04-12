<template>
<body >
  <div class="container d-flex flex-column justify-content-center ">
    <div class="bgimg jusify-content-center">
    <h1>Just dance</h1>
    <li><i>Twist</i></li>
    <li><i>Kneel</i></li>
    <li><i>backflip</i></li>
    <li><i>bend</i></li>
    <li><i>crouch</i></li>
    <li><i>Handwave</i></li>
    <li><i>Lay down</i></li>
    </div>
    <jump-start-app></jump-start-app>
    <icons-app></icons-app>
    <!-- add moving js element words side to side -->
      <!-- fade in list items -->
    
    <div class="justify-content-center row-8 ">
    <small class="red"><i>Page Completed By: Jason Ure August of 2020</i></small>
    <div>Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"     title="Flaticon">www.flaticon.com</a></div>
    <div>Icons made by <a href="https://www.flaticon.com/authors/mangsaabguru" title="mangsaabguru">mangsaabguru</a> from <a href="https://www.flaticon.com/"     title="Flaticon">www.flaticon.com</a></div>
    </div>
    

      
  <!-- three icons martin lurthar king, indian dance Icon, womens writes leader-->
      </div>
    </body>
  
</template>

<script>
import jumpStart from './components/JumpStart.vue'
import icons from './components/icons.vue'
export default {
components: {
  jumpStartApp: jumpStart,
  iconsApp: icons

}

}
</script>

<style>
html, body {
  background-color: black;
  color: white;
}
  .bgimg {
    background-position: center;
    
    height: 300px;
    background-image: url(./components/img/bgimg2.jpg);
    color: white;
    background-repeat: no-repeat;

  }
  .red {
    color:crimson;
  }
  .blue{
    color: blue;
    font-size: .6em;
    background-color: yellow;
  
  }
  li {
    text-decoration: none;
    list-style-type: none;
  }
  .global {
    font-size: 18.5px;
    background-color: black;
    color:white;
  }
  .box {
    border: 1px dashed white;
  }
</style>
