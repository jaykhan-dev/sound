<template>
  <audio
    src="https://khanquest-heroku.s3.amazonaws.com/Be_Water.mp3"
    ref="audioPlayer"
  >
    Your browser does not support the
    <code>audio</code> element.
  </audio>
  <div
    class="text-white flex justify-between space-x-4 border p-2 rounded-full px-8 border-gray-700 text-2xl bg-gradient-to-r from-blue-500 to-green-600"
  >
    <button @click="play">
      <i class="fa-solid fa-play hover:text-xl duration-200"></i>
    </button>
    <button @click="pause">
      <i class="fa-solid fa-pause hover:text-xl duration-200"></i>
    </button>
    <button @click="stop">
      <i class="fa-solid fa-stop hover:text-xl duration-200"></i>
    </button>

    <a
      href="https://music-endeavr.netlify.app"
      target="_blank"
      rel="noopener noreferrer"
      ><img
        src="../assets/endeavr-white.svg"
        alt=""
        width="30"
        class="hover:scale-95 duration-300"
    /></a>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      currentTime: 0,
      seekValue: 0,
    };
  },
  methods: {
    play() {
      this.$refs.audioPlayer.play();
    },
    pause() {
      this.$refs.audioPlayer.pause();
    },
    stop() {
      const { audioPlayer } = this.$refs;
      audioPlayer.pause();
      audioPlayer.currentTime = 0;
    },
  },
};
</script>
