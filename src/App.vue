<script>
import Header from './components/UI/Header.vue'
import Footer from './components/UI/Footer.vue'

import Main from './Pages/Main.vue'

export default {
  components: { Header, Footer, Main }
}
</script>

<template>
  <header>
    <Header />
  </header>

  <main>
    <Main />
  </main>

  <footer>
    <Footer />
  </footer>
</template>

<style>

</style>
