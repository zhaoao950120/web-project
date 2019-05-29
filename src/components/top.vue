<template>
  <el-row>
    <el-col :span="24">
      <div class="grid-content bg-purple-dark">
        <div class="w1100">
          <ul class="ul1">
            <li>中亿财经网</li>
            <li>中亿理投师</li>
            <li>股票</li>
            <li>外汇</li>
            <li>期货</li>
            <li>黄金</li>
            <li>区块链</li>
            <li>中亿汇评</li>
            <li>中亿社区</li>
          </ul>
          <ul class="ul2">
            <li>登录</li>
            <li>注册</li>
          </ul>
        </div>
      </div>
    </el-col>
  </el-row>
</template>

<style scoped>
* {
  padding: 0;
  margin: 0;
  list-style: none;
}
.el-row {
  /* margin-bottom: 20px; */
}
.bg-purple-dark {
  background: #99a9bf;
}

.grid-content {
  /* border-radius: 4px; */
  min-height: 36px;
  /* width: 1920px; */
  height: 42px;
  background-color: #333333;
  width: 100%;
}
.w1100 {
  width: 1100px;
  height: 42px;
  margin: auto;
  /* background-color: #567; */
  display: flex;
}
.w1100 .ul1 {
  width: 656px;
  /* height: 15px; */
  font-size: 14px;
  font-family: SourceHanSansSC-Regular;
  font-weight: 400;
  color: rgba(204, 204, 204, 1);
  line-height: 42px;
  display: flex;
}
.w1100 .ul2 {
  width: 100px;
  font-size: 14px;
  font-family: SourceHanSansSC-Regular;
  font-weight: 400;
  color: rgba(204, 204, 204, 1);
  line-height: 42px;
  display: flex;
  justify-content: flex-end;
  margin-left: 374px;
}
.w1100 .ul1 li {
  /* flex-direction: row;
  justify-content: center; */
  padding: 0 10px;
  /* flex: 1; */
}
.w1100 .ul2 li {
  flex: 1;
}
</style>
<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  // name: "home",
};
</script>
