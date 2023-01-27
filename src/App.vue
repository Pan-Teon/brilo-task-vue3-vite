<template>
  <main class="main-content">
    <div class="container-max">

      <Header />
      <AboutMe />
      <Works />
      <Footer />

    </div>
  </main>
</template>

<script>
import Header from './components/Header.vue'
import AboutMe from './components/AboutMe.vue'
import Works from './components/Works.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    AboutMe,
    Works,
    Footer
  }
}
</script>
