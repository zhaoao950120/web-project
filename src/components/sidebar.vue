<template>
  <div class="box">
    <div class="w1100">
      <div class="home">
        <h2>行情中心</h2>
        <h3>Market data</h3>
        <el-menu default-active="2" class="el-menu-vertical-demo">
          <el-submenu index="1">
            <template slot="title">
              <!-- <i class="el-icon-location"></i> -->
              <span>我的自选</span>
            </template>
          </el-submenu>

          <el-submenu index="2">
            <template slot="title">
              <!-- <i class="el-icon-location"></i> -->
              <span>沪深股市</span>
            </template>
          </el-submenu>

          <el-submenu index="3">
            <template slot="title">
              <!-- <i class="el-icon-location"></i> -->
              <span>港股股市</span>
            </template>
          </el-submenu>

          <el-submenu index="4">
            <template slot="title">
              <!-- <i class="el-icon-location"></i> -->
              <span>美股股市</span>
            </template>
          </el-submenu>
        </el-menu>
      </div>
    </div>
  </div>
</template>
<style scoped>
* {
  margin: 0;
  padding: 0;
}
/* .box {
  width: 100%;
}
.w1100 {
  width: 1100px;
  margin: auto;
} */
.home {
  width: 135px;
  height: 1748px;
}
h2 {
  font-size: 25px;
  font-family: MicrosoftYaHei-Bold;
  font-weight: bold;
  color: rgba(76, 139, 244, 1);
  margin-top: 18px;
}
h3 {
  font-size: 19px;
  font-family: MicrosoftYaHeiLight;
  font-weight: 300;
  color: rgba(76, 139, 244, 1);
  padding-bottom: 15px;
  border-bottom: 1px dashed rgba(230, 230, 230, 1);
}
</style>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  // name: "home",
};
</script>
