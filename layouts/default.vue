<template>
  <div class="flex flex-col h-screen bg-gray-50">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'

export default {
  components: {
    Header,
    Footer
  }
}
</script>
