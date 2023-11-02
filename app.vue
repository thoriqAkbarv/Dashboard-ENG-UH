<template>
  <div>
    <Header />
    <ImageHero />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import ImageHero from './components/ImageHero.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    ImageHero,
    Main,
    Footer
  }
}
</script>
