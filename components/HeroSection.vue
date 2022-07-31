<template>
  <div id="hero-section" class="bg-fixed">
    <div id="hero-filter" class="flex justify-center bg-black">
      <div class="lg:w-1/2 my-20">
        <div class="grid place-items-center my-20 py-20">
          <h2 class="lg:text-8xl text-5xl text-center">Building a</h2>
          <div class="">
            <h1 class="lg:text-9xl text-6xl italic">Sound</h1>
          </div>
          <h2 class="lg:text-8xl text-6xl">Foundation</h2>
        </div>

        <div class="my-20 px-12 border-l-4 border-white">
          <h2 class="uppercase font-bold text-gray-400 my-4">Story</h2>
          <h2 class="text-6xl">Humble beginnings</h2>
          <div class="grid lg:grid-cols-2 my-8 gap-8 text-white">
            <p class="text-xl">
              The internet is an evolving phenomenon. It has given a voice to
              the voiceless, opportunities to the vulnerable, and knowledge to
              the seekers. But it is not perfect and those who would use it for
              gaining power, have so much of it, that it boggles the mind.
            </p>
            <p class="text-xl">
              Strangely, the internet is coming full-circle. The first version
              was decentralized, where anyone who wanted a website, had to setup
              their own server and share information in a P2P fashion. With the
              blockchain, the same principles are now driving the new flavor of
              applications being built.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.box {
  transform: rotate(45deg);
}

.element {
  transform: rotate(-45deg);
}

#hero-section {
  background-image: url('../assets/fluid-bg.jpg');
  background-position: left;
  background-repeat: no-repeat;
  background-size: cover;
}

#hero-filter {
  opacity: 90%;
}
</style>
