<template>
<div class="container  fixed-top">
  <div class="row justify-content-end text-end">
    <div class="col-sm-12">

  <button class="btn my-2" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">
    <i class="fa-solid fa-bars"></i>
  </button>

      <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
        <div class="offcanvas-header">
          <h5 id="offcanvasRightLabel">Menu</h5>
          <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
          <!-- <router-link to="/">Home</router-link><br> -->
          <a href="#home">Home</a><br>
          <a href="#about">About</a><br>
          <a href="#resume">Resume</a><br>
          <a href="#testimonial">Testimonial</a><br>
          <a href="#projects">Projects</a><br>
          <a href="#contact">Contact</a><br>
        </div>
      </div>
      
    </div>
  </div>
</div>

    

    </template>
    
    <script>
    export default {
        
    }
    </script>
    
    <style scoped>
button{
  background-color: #9198a0;
}

    nav {
        padding: 30px;
      }
      
      nav a {
        font-weight: bold;
        color: #2c3e50;
      }
      
      nav a.router-link-exact-active {
        color: #42b983;
      } 
    </style>