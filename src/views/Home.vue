<template>
  <div class="home">
    <Navbar/>
    <Hero/>
    <Tentang/>
    <Howitworks/>
    <More/>
    <Footer/>
  </div>
</template>

<script>
import Hero from '@/components/Hero.vue'
// @ is an alias to /src

import Navbar from '@/components/Navbar.vue'
import Tentang from '../components/Tentang.vue'
import Howitworks from '../components/Howitworks.vue'
import More from '../components/More.vue'
import Footer from '../components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    Tentang,
    Howitworks,
    More,
    Footer
  }
}
</script>
