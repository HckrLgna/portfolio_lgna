<template>
  <div>
    <NavBar />
    <div class="container-fluid mt-5 pt-5">
      <Hero />
      <services />
      <Projects />
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
 
import Hero from '@/components/Hero.vue'
import NavBar from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import Services from '@/components/Services.vue'
import Projects from '@/components/Projects.vue'
export default {
  name: 'HomeView',
  components: {
    Hero,
    NavBar,
    Services,
    Projects,
    Footer
  }
}
</script>
