<template>
  <div>
    <header>
      <Navbar />
    </header>

    <main>
      <Reel />
    </main>
  </div>
</template>

<script>
import Navbar from './components/Navbar';
import Reel from './components/Reel';

export default {
  name: 'App',
  components: {
    Navbar,
    Reel
  },
}
</script>

<style>
  :root {
    overflow: auto;
  }
</style>
