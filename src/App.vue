<template>
<NavbarVue></NavbarVue>

  <router-view></router-view>

</template>

<script>
// @ is an alias to /src

import NavbarVue from './components/Navbar.vue';


export default {
  name: 'HomeView',
  components: {
    NavbarVue
}
}
</script>


<style>
#app {
  font-family: raleway;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  transition: all 0.3s ease-in-out;
}

h1{
  border-bottom: 1px solid rgb(110, 110, 110);
}

p{
  font-size: 1.1rem;
}

section{
  min-height: 100vh;
}


</style>
