<template>
    <section id="testimonial">
        

<div class="container py-2">
    <div class="row justify-content-center">
        <h1>Testimonial</h1>
        <div v-for="item in testimonial" class="col-sm-12 col-md-5 mx-2 my-2 card-client">
            <div class="user-picture">
            <img :src="item.img" alt="">
            </div>
       
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col">
                        <h1 class="name">{{item.Name}}</h1>
                        <h5>{{item.Position}}</h5>
                    </div>
                </div>
            </div>
            
     <div class="card-main text-start py-1">
<p>"{{item.comment}}"</p>
    </div>
        </div>
    </div>
</div>

    </section>
    </template>
    <script>
    export default {
        data() {
        return {
            testimonial: [
                {
                    Name: 'Shane Stevens',
                    Position: 'Assistant Lecturer',
                    img: 'https://i.postimg.cc/K8YR8xNY/me3-removebg.png',
                    comment: 'Reece is an outgoing, hardworking, creative web developer. Who sets out to achieve his goals through perseverance and determination. I see a bright future filled with prosperity being set in front of him, with his iron will to overcome any impediments that comes he way. As such he has the set skills to fulfill any task that will be given to him, making him a great asset to any business or company.',
                },
                {
                 
                    Name: 'Shane Stevens',
                    Position: 'Assistant Lecturer',
                    img: 'https://i.postimg.cc/K8YR8xNY/me3-removebg.png',
                    comment: 'Reece is an outgoing, hardworking, creative web developer. Who sets out to achieve his goals through perseverance and determination. I see a bright future filled with prosperity being set in front of him, with his iron will to overcome any impediments that comes he way. As such he has the set skills to fulfill any task that will be given to him, making him a great asset to any business or company.',
              
                }
            ]
        }
    }
    }
    </script>
    <style scoped>
    .card-client {
        background-color: rgba(255, 149, 11, 0.384);
        padding-top: 25px;
        padding-bottom: 25px;
        padding-left: 20px;
        padding-right: 20px;
        border: 4px solid rgba(255, 149, 11, 0.247);
        box-shadow: 0 6px 10px rgba(207, 212, 222, 1);
        border-radius: 10px;
        color: #fff;
        transition: all 0.3s ease;
      }
      
      
      .user-picture {
        overflow: hidden;
        object-fit: cover;
        width: 8rem;
        height: 8rem;
        border: 4px solid rgba(255, 149, 11, 0.247);
        border-radius: 999px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: auto;
      }

      .card-main{
        border-top: 1px solid white;
      }

      img{
        height: 8rem;
        -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
  filter: grayscale(100%);
  transition: all 0.3s ease-in-out;
      }

      img:hover{
        -webkit-filter: grayscale(0%); /* Safari 6.0 - 9.0 */
        filter: grayscale(0%);
      }

      .name{
        border-bottom: none;
      }
      

    </style>