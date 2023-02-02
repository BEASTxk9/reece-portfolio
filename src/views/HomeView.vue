<template>
<header class="fixed-top">
</header>
<HomeVue></HomeVue>

<main>


  <AboutVue></AboutVue>

  <Resume></Resume>

  <Testimonial></Testimonial>

  <Project></Project>

 <Contact></Contact>
</main>

<footer>

  <div class="container">
    <div class="row">

<div class="col-sm-12">

<div class="container">
  <div class="row">

    <div class="col-sm-6">
      contact info
    </div>

    <div class="col-sm-6">
      social links
    </div>

  </div>
</div>


</div>

      <div class="col-sm-12 ft">
<p> &copy; 2023 Made By Reece.</p>
      </div>
    </div>
  </div>

</footer>

</template>

<script>
// @ is an alias to /src
import Contact from '@/components/Contact.vue';
import Project from '@/components/Project.vue';
import Resume from '@/components/Resume.vue';
import Testimonial from '@/components/Testimonial.vue';
import AboutVue from '../components/About.vue';
import HomeVue from '../components/Home.vue';

export default {
  name: 'HomeView',
  components: {
    HomeVue,
    AboutVue,
    Resume,
    Testimonial,
    Project,
    Contact
}
}
</script>

<style scoped>
header{
  background-image: url('https://i.postimg.cc/0jNrrc36/mountains-1412683-1280.png');
  background-size: cover;
  background-repeat: no-repeat;
  z-index: -1;
  min-height: 100vh;
}
main{
  z-index: 2;
  background-color: rgba(250, 235, 215, 0.842);
}

footer{
  color: white;
  background-color: rgba(0, 0, 0, 0.712);
  padding: 2rem;
}

.ft{
  border-top: 1px solid white;
}
</style>
