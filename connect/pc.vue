<template>
  <div class="pc">pc页面
    <img src="./images/flash.png" alt="">
    <div class="second">第二阶段的文字</div>
    <div class="rule-wrap">
      <p>1.测试代码</p>
      <p>2.测试代码</p>
      <p>3.测试代码</p>
      <p>4.测试代码</p>
      <p>5.测试代码</p>
      <p>6.测试代码</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pc",
  data() {
    return {
      isEnabled:false,
    }
  },
}
</script>

<style>
.second {
  width: 200px;
  height: 100px;
  background-color: pink;
}
</style>