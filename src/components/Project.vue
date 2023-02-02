<template>
    <section id="projects">
        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                       <h1>Projects</h1>
                </div>
            </div>
        </div>

        <div class="container py-5">
            <div class="row">

<!-- modal 1 -->
<div class="col-sm-12 col-md-4">

<!-- Button trigger modal -->

   <img class="py-3" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="" data-bs-toggle="modal" data-bs-target="#exampleModal">
  
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Project name</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
         <img class="w-50" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="">
        </div>
        <div class="modal-footer">
            <a href="#" class="btn btn-secondary" target="_blank">git hub link</a>
            <a href="#" class="btn btn-secondary" target="_blank">live link</a>
        </div>
      </div>
    </div>
  </div>
  

</div>

<!-- modal 2 -->
<div class="col-sm-12 col-md-4">

    <!-- Button trigger modal -->
    
       <img class="py-3" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="" data-bs-toggle="modal" data-bs-target="#exampleModal2">
      
      <!-- Modal -->
      <div class="modal fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel2" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel2">Project name2</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
             <img class="w-50" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="">
            </div>
            <div class="modal-footer">
                <a href="#" class="btn btn-secondary" target="_blank">git hub link</a>
                <a href="#" class="btn btn-secondary" target="_blank">live link</a>
            </div>
          </div>
        </div>
      </div>
      
    
    </div>
    
    <!-- modal 3 -->
<div class="col-sm-12 col-md-4">

    <!-- Button trigger modal -->
    
       <img class="py-3" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="" data-bs-toggle="modal" data-bs-target="#exampleModal3">
      
      <!-- Modal -->
      <div class="modal fade" id="exampleModal3" tabindex="-1" aria-labelledby="exampleModalLabel3" aria-hidden="true">
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel2">Project name3</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
             <img class="w-50" src="https://i.postimg.cc/3wt6HMBm/meeting-2284501-1920.jpg" alt="">
            </div>
            <div class="modal-footer">
                <a href="#" class="btn btn-secondary" target="_blank">git hub link</a>
                <a href="#" class="btn btn-secondary" target="_blank">live link</a>
            </div>
          </div>
        </div>
      </div>
      
    
    </div>


            </div>
        </div>
     
    </section>
    </template>
    <script>
    export default {
        
    }
    </script>
    <style scoped>

    img{
        height: 30%;
        transition: all 0.3s ease-in-out;
    }  
    
    img:hover{
        height: 33%;
    }

    </style>