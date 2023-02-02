<template>
    <section id="resume">
        <div class="container">
            <div class="row justify-content-center">
                <h1>Resume</h1>

                     <!-- work -->
<h2 class="py-3">Work experience</h2>
           
                <div id="card" v-for="item in work" class="col-sm-12 col-md-5 mx-2 my-2">
                  <!-- header -->
                    <div class="container header">
                        <div class="row">
                            <div class="col-sm-6  text-start">
                                <h3> {{ item.Company }}</h3>
                            </div>
                            <div class="col-sm-6 text-end">
                                <h3> {{ item.year }}</h3>
                            </div>
                        </div>
                    </div> 
                         <!-- main -->
                    <div class="container py-2">
                        <div class="row text-start">
                            <li><b>Role:</b>{{ item.role }}</li>
                    <li><b>Skills:</b>{{ item.skills }}</li>
                    <li><b>Responsibilities:</b>{{ item.comment }}</li>
                        </div>
                    </div>
                 
                    
                       </div>

                     
<!-- education -->
  <h2 class="py-3">Education</h2>
                       <div id="card" v-for="item in education" class="col-sm-12 col-md-5 mx-2 my-2">
                        <!-- header -->
                          <div class="container header">
                              <div class="row">
                                  <div class="col-sm-6  text-start">
                                      <h3> {{ item.school }}</h3>
                                  </div>
                                  <div class="col-sm-6 text-end">
                                      <h3> {{ item.year }}</h3>
                                  </div>
                              </div>
                          </div> 
                               <!-- main -->
                          <div class="container py-2">
                              <div class="row text-start">
                          <li><b>Skills:</b>{{ item.skills }}</li>
                          <li><b>Responsibilities:</b>{{ item.comment }}</li>
                              </div>
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
            work: [
                {
                    Company: 'LCA',
                    year: '2022',
                    role: 'job role',
                    skills: 'html',
                    comment: 'What u did',
                },
                {
                    Company: 'LCA',
                    year: '2022',
                    role: 'job role',
                    skills: 'html',
                    comment: 'What u did',
                }
            ],
            education: [
                {
                    school: 'LCA',
                    year: '2022',
                    skills: 'html',
                    comment: 'What u did',
                },
                {
                    school: 'LCA',
                    year: '2022',
                    skills: 'html',
                    comment: 'What u did',
                }
            ]
        }
    }
}
</script>
<style scoped>
#card{
    background-color: rgba(255, 149, 11, 0.247);
    border-radius: 20px;
    padding: 5px;
}

.header{
    border-bottom: 1px solid rgba(128, 128, 128, 0.651);

}
</style>