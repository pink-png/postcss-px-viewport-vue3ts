<script setup lang="ts">
</script>

<template>
  <div class="container">
    <div class="left">left</div>
    <div class="center"></div>
    <div class="right">right</div>
  </div>
</template>

<style scoped lang="scss">
.container {
  // https://blog.csdn.net/weixin_41487448/article/details/92830761
  height: inherit;
  display: flex;
  
  .left {
    width: 100px;
    background-color: red;
  }

  .center {
    flex: 1;
    background-color: yellowgreen;
  }

  .right {
    width: 100px;
    background-color: red;
  }
}
</style>
