<template>
    <section>
        <div class="container">
            <div class="row justify-content-center">
                <h1>Resume</h1>

                <div id="card" v-for="item in resume" class="col-sm-12 col-md-5 mx-2 my-2">
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
                    <p>Skills: {{ item.skills }}</p>
                    
                       </div>
            </div>
        </div>

    </section>
</template>
<script>
export default {
    data() {
        return {
            resume: [
                {
                    Company: 'LCA',
                    year: '2022',
                    skills: 'html',
                },
                {
                    Company: 'LCA',
                    year: '2022',
                    skills: 'html',
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