<script setup>
import SideNav from "./components/SideNav.vue";
import TroisJS from "./components/TroisJS.vue";
import AudioPlayer from "./components/AudioPlayer.vue";
</script>

<template>
  <div class="h-screen relative">
    <img
      src="./assets/sound-logo-white.png"
      alt="Sound Co Logo"
      width="75"
      class="absolute top-5 right-5 hover:scale-95 duration-300"
    />
    <p class="text-sm absolute bottom-5 left-5 text-white">
      © 2022 SOUND CO. The Enso-Dragon logo are trademarks of Sound Co.
    </p>
    <div class="absolute bottom-5 right-5">
      <SideNav />
    </div>
    <div class="absolute top-5 left-5">
      <AudioPlayer />
    </div>
    <TroisJS />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Chakra+Petch&family=Prompt&family=Space+Mono&display=swap");

/*
font-family: 'Chakra Petch', sans-serif;
font-family: 'Prompt', sans-serif;
font-family: 'Space Mono', monospace;
*/

h1 {
  font-family: "Space Mono", monospace;
}

h2 {
  font-family: "Chakra Petch", sans-serif;
}
p {
  font-family: "Chakra Petch", sans-serif;
}
</style>
