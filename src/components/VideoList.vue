<template>
  <ul class="video-list">
    <li v-for="n in 4" :key="n">
      <div class="list-img">
        <img src="../assets/imgs/1.png" alt />
      </div>
      <div class="list-msg">
        <p>潮流合伙人 全员素颜</p>
        <p>凡凡大勋教你怎么玩</p>
      </div>
    </li>
  </ul>
</template>

<style scoped>
.video-list {
  width: 100%;
  height: auto;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
.list-img {
  width: 3.3rem;
  height: 2rem;
  margin-bottom: 0.16rem;
}
.list-img img {
  width: 100%;
  height: 100%;
}
.list-msg p {
  width: 3rem;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.list-msg p:nth-child(1) {
  height: 0.4rem;
  font-size: 0.28rem;
  font-weight: 500;
  line-height: 0.4rem;
  color: rgba(51, 51, 51, 1);
}
.list-msg p:nth-child(2) {
  height: 0.33rem;
  font-size: 0.24rem;
  font-weight: 400;
  line-height: 0.33rem;
  color: rgba(153, 153, 153, 1);
}
</style>