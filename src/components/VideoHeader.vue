<template>
  <div class="video-header">
    <div>
      <div class="video-line"></div>
      <div class="video-title">免费视频</div>
    </div>
    <div>
      <div class="video-more">
        <span>更多</span>
        <span class="iconfont">&#xe641;</span>
      </div>
    </div>
  </div>
</template>


<style scoped>
@import url("../assets/icon.css");
.video-header {
  width: 100%;
  height: 0.5rem;
  padding: 0.4rem 0 0.32rem 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.video-header > div {
  display: flex;
  align-items: center;
}
.video-line {
  width: 0.08rem;
  height: 0.3rem;
  background: rgba(63, 90, 143, 1);
  border-radius: 0.2rem;
  margin-right: 0.16rem;
}
.video-title {
  font-size: 0.36rem;
  font-weight: bold;
  line-height: 0.5rem;
  color: rgba(51, 51, 51, 1);
}
.video-more {
  font-size: 0.26rem;
  font-weight: 400;
  line-height: 0.37rem;
  color: rgba(51, 51, 51, 1);
}
</style>