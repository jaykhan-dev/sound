<template>
  <div class="flex justify-center my-20 py-20">
    <div class="grid lg:grid-cols-3 gap-4 lg:w-1/2">
      <!-- COL -->
      <div class="hover:scale-110 duration-300">
        <img src="../assets/distant1.jpg" alt="" />
      </div>
      <!-- COL -->
      <div id="image-2" class="">
        <img src="../assets/distant2.jpg" alt="" class="translate-y-12" />
      </div>
      <!-- COL -->
      <div id="image-3">
        <img src="../assets/distant3.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<style>
#image-2 {
  transform: translate(0px, 50px);
}

#image-2:hover {
  scale: 110%;
}

#image-3 {
  transform: translate(0px, 100px);
}
</style>
