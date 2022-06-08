<script setup>
import SideNav from "./components/SideNav.vue";
import TroisJS from "./components/TroisJS.vue";
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
    <TroisJS />
  </div>
</template>

<style></style>
