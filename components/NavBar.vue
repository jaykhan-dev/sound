<template>
  <nav
    class="flex justify-between uppercase text-2xl space-x-4 py-4 p-4 bg-black text-white border-b border-gray-700 fixed top-0 w-full"
  >
    <router-link to="/">
      <h2 class="">Home</h2>
    </router-link>
    <div class="flex space-x-4">
      <router-link to="/projects">
        <h2 class="">Projects</h2>
      </router-link>

      <router-link to="/contact">
        <h2 class="">Contact</h2>
      </router-link>
    </div>
  </nav>
</template>

<script></script>
