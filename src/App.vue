<template>
  <div>
    <Navbar/>

    <Footer/>

    
  </div>
  <router-view/>

</template>

<script>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer
  
  }
}
</script>

<style>

</style>



