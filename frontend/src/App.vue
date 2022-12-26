<template>
  <div class="container">
    <div class="video-wrapper">
      <video
        class="video-player"
        loop
        src="https://vod-progressive.akamaized.net/exp=1672052521~acl=%2Fvimeo-prod-skyfire-std-us%2F01%2F840%2F22%2F554200859%2F2621558841.mp4~hmac=12998e784835e4fda03248c7f83f57f19179d6a89078372aa9dec1cbb7942eee/vimeo-prod-skyfire-std-us/01/840/22/554200859/2621558841.mp4"
      ></video>
    </div>
  </div>
</template>

<script lang="ts">
import Home from "./components/Home.vue";
export default {
  setup() {},
  components: { Home },
  created() {},
};
</script>

<style>
.container {
  height: 100vh;
  display: grid;
  place-items: center;
  background-color: black;
}
</style>
<!-- 
  container
   -video-wrapper
 -->
