<template>
    <section id="about">
        <!-- heading -->
        <div class="container pt-5 pb-2">
            <div class="row justify-content-center">
                <div class="col-sm-12">
                           <h1>About me!</h1>
                </div>
            </div>
        </div>

        <div class="container pt-2">
            <div class="row">
                <!-- img -->
                <div class="col-sm-12 col-lg-6">
                    <img src="https://i.postimg.cc/7L7PKbjZ/people-2013447-1920.jpg" alt="me">
                                    </div>
                <!-- about -->
                <div class="col-sm-12 col-lg-6 text-start about">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias harum exercitationem quaerat, vel sapiente deserunt facere quisquam corrupti neque, beatae, cupiditate nihil totam corporis labore. Reiciendis quos harum repellendus dolor.
                    Ut harum blanditiis rerum fuga molestias quis perspiciatis doloribus unde in officia quos repudiandae labore consequatur architecto illo, possimus, sit velit totam voluptatem adipisci expedita asperiores esse, minus itaque. Perspiciatis!
                    Fuga odit veniam, ut odio laboriosam magnam amet quo aliquid esse facilis assumenda architecto optio dolor deleniti, numquam, velit repudiandae culpa minus rem repellendus recusandae neque mollitia ipsum. Repudiandae, soluta!
                    Doloribus explicabo porro dolorum eum illum quam, atque corporis voluptatum, dignissimos tempora magni doloremque tempore numquam? Error sed nobis voluptate provident possimus enim, aliquid et accusantium maiores quos corporis officia!
                    Sint odio corrupti exercitationem sunt assumenda commodi laudantium, nobis eum qui possimus. Id sit adipisci c
                    Temporibus blanditiis veritatis nesciunt incidunt eveniet recusandae iste vel saepe, obcaecati cumque rem maiores repudiandae in reprehenderit voluptate minima quae laudantium a labore. Laborum itaque eaque minus quisquam laudantium dolorum?
                    Nostrum fugiat voluptatibus odit ipsum nam mollitia quaerat aspernatur provident consequuntur deleniti quae expedita atque, repellat illo? Incidunt, dolorum culpa nihil voluptate sunt quae eum quasi vel amet ipsam distinctio.
                    Sunt earum recusandae sed libero deleniti tempora quod nihil dolorum inventore repellendus corrupti odio dignissimos, iusto doloremque omnis eveniet architecto ex reiciendis neque et fugiat ipsum a quasi? Quisquam, aperiam.
                    Doloribus explicabo porro dolorum eum illum quam, atque corporis voluptatum, dignissimos tempora magni doloremque tempore numquam? Error sed nobis voluptate provident possimus enim, aliquid et accusantium maiores quos coi.</p>
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
    section{
        z-index: 2px;
        
    }

    img{
        opacity: 0.8;
        border-radius: 10px;
        height: 80%;
    }


    @media only screen and (max-width: 990px){
        .about{
           position: relative;
           top: -9rem;
        }
       }

    @media only screen and (max-width: 680px){
     img{
        height: 70%;
     }

     .about{
        position: relative;
        top: -13rem;
     }
    }

    
    @media only screen and (max-width: 420px){
        img{
           height: 60%;
        }

        
     .about{
        position: relative;
        top: -18rem;
     }
   
       }
        
    @media only screen and (max-width: 365px){
        img{
           height: 48%;
        }

        .about{
            position: relative;
            top: -25rem;
         }
   
       }
    </style>