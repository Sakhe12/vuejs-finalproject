<template>
  <Navbar></Navbar>
  <router-view/>
  <Footer></Footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dosis&display=swap');
#app {
  font-family: 'Dosis', sans-serif;
  background-color: #61876E;
  padding-bottom: 1rem;

}
</style>
<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default {
  components : {
    Navbar,
    Footer
  }
}
</script>