<template>
  <div class="about">
    <Navbar/>
    <Developer/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
import Developer from '../components/Developer.vue'
export default {
  components: { Navbar,Footer, Developer },
nama: 'About'
}
</script>

<style>

</style>