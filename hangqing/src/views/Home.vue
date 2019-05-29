<template>
  <el-container>
    <!-- 头部 -->
    <el-header height="112px">
      <top></top>
      <logo></logo>
    </el-header>
    <!-- 主体 -->
    <div style="background-color:#f5f5f5;width:100%;padding-top: 27px;">
      <el-container class="mine">
        <el-aside width="135px" style="background-color:#fff">
          <sidebar></sidebar>
        </el-aside>
        <el-main style="padding:0;margin-left:20px">
          <div class="shichang" style>
            <shichang></shichang>
          </div>
        </el-main>
      </el-container>
    </div>
    <!-- 底部 -->
    <foot></foot>
  </el-container>
</template>

<style scoped>
.box {
  width: 100%;
}
.w1100 {
  width: 110px;
  margin: auto;
}
.mine {
  width: 1100px;
  margin: auto;
}
.shichang {
  width: 944px;
  height: 443px;
  text-align: left;
  background-color: #fff;
  margin-top: -20px;
  padding-left: 18px;
}
</style>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import sidebar from "@/components/sidebar.vue";
import top from "@/components/top.vue";
import logo from "@/components/logo.vue";
import foot from "@/components/foot.vue";
import shichang from "@/components/index/shichang.vue";

export default {
  // name: "home",
  components: {
    // HelloWorld,
    sidebar,
    top,
    logo,
    foot,
    shichang
  }
};
</script>
