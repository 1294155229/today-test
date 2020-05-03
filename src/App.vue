<template>
  <div id="app">
    <div class="video">
      <video-header></video-header>
      <video-list></video-list>
    </div>
  </div>
</template>

<script>
import VideoHeader from "./components/VideoHeader";
import VideoList from "./components/VideoList";
export default {
  components: {
    VideoHeader,
    VideoList
  }
};
</script>

<style scoped>
#app {
  width: 7.5rem;
  margin: 0 auto;
  font-family: PingFang SC;
}
.video {
  width: 7.5rem;
  padding: 0 0.32rem;
  box-sizing: border-box;
}
</style>
