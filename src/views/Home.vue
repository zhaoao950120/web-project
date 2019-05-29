<template>
  <div class="home">
    <top></top>
    <header></header>
    <logo></logo>
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <el-button type="primary">主要按钮</el-button> -->
    <!-- <el-button type="primary" size="medium" class="btn">主要按钮</el-button> -->

    <div class="box">
      <div class="w1100">
        <sidebar></sidebar>
      </div>
      <foot></foot>
    </div>
  </div>
</template>
<style scoped>
.box {
  width: 100%;
}
.w1100 {
  width: 110px;
  margin: auto;
}
</style>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import sidebar from "@/components/sidebar.vue";
import top from "@/components/top.vue";
import logo from "@/components/logo.vue";
import foot from "@/components/foot.vue";

export default {
  // name: "home",
  components: {
    // HelloWorld,
    sidebar,
    top,
    logo,
    foot
  }
};
</script>
