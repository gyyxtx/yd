<template>
  <div id="app">
    <van-button type="primary">主要按钮</van-button>
    <div class="a"></div>
    <router-view/>
  </div>
</template>

<style lang="less">
.a{
  width:100px;
  height: 100px;
  background: red;
}
</style>
