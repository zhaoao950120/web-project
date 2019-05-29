<template>
  <div>
    <el-row>
      <el-col :span="24">
        <div class="grid-content bg-purple-dark">
          <div class="w1100">
            <h1>
              <img src="../assets/logo.png" alt>
            </h1>
            <div class="searh">
              <el-input class="input" placeholder="请输入内容" prefix-icon="el-icon-search" size="mini"></el-input>
              <div>
                <el-button type="primary" class="btn">主要按钮</el-button>
                <!-- <el-button type="success">成功按钮</el-button> -->
              </div>
            </div>
          </div>
        </div>
      </el-col>
    </el-row>
    <!-- <el-button type="primary" size="medium" class="btn">主要按钮</el-button> -->
  </div>
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
  background: #fff;
}

.grid-content {
  /* border-radius: 4px; */
  min-height: 36px;
  /* width: 1920px; */
  height: 70px;
  background-color: #ffffff;
  width: 100%;
}
.w1100 {
  width: 1100px;
  height: 70px;
  margin: auto;
  background-color: #fff;
  display: flex;
}
.w1100 h1 img {
  margin-top: 21px;
}
.searh {
  margin-left: 100px;
}
</style>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  // name: "home",
};
</script>
