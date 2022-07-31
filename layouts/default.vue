<template>
  <div class="bg-black text-white">
    <NavBar />
    <Nuxt />
    <FooterBar />
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue'
import FooterBar from '../components/FooterBar.vue'
export default {
  components: {
    NavBar,
    FooterBar,
  },
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

body {
  cursor: crosshair;
}

h1 {
  font-family: 'Bodoni Moda', serif;
}
h2,
p {
  font-family: 'Urbanist', sans-serif;
}

/* width */
::-webkit-scrollbar {
  width: 10px;
  background: black;
}

/* Track */
::-webkit-scrollbar-track {
  border-radius: 10px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: rgb(15, 1, 63);
  border-radius: 10px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #312f2f;
}
</style>
