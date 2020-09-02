<template>
  <div>
    <header>
      <Navbar />
    </header>

    <main>
      <Reel />
      <Videos />
    </main>

    <footer>
      <Footer />
    </footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Reel from './components/Reel'
import Footer from './components/Footer'
import Videos from './components/Videos'

export default {
  name: 'App',
  components: {
    Navbar,
    Reel,
    Footer,
    Videos,
  },
}
</script>

<style>
:root {
  overflow: auto;
}
</style>
