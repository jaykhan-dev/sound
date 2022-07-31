<template>
  <main class="">
    <HeroSection />
  </main>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue'
export default {
  name: 'IndexPage',
  components: { HeroSection },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Black+Ops+One&family=Bodoni+Moda:ital,opsz,wght@0,6..96,500;1,6..96,500&family=Share+Tech+Mono&family=Urbanist:wght@400;500;900&display=swap');

/*
font-family: 'Black Ops One', cursive;
font-family: 'Bodoni Moda', serif;
font-family: 'Share Tech Mono', monospace;
font-family: 'Urbanist', sans-serif;
*/

h1 {
  font-family: 'Bodoni Moda', serif;
}
h2,
p {
  font-family: 'Urbanist', sans-serif;
}
</style>
