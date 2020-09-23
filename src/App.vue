<template>
  <el-container id="app">
    <el-header class="el-header">
      <Header />
    </el-header>
    <el-main class="el-main">
      123123
    </el-main>
    <el-footer class="el-footer">
      <Footer />
    </el-footer>
  </el-container>
</template>

<script>
import Footer from "./Footer";
import Header from "./Header";

export default {
  name: "app",
  components: {
    Footer,
    Header
  }
};
</script>

<style global lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body,
html,
#app {
  .el-header {
    padding: 0;
    height: 40px;
    font-size: 16px;
  }

  .el-footer {
    padding: 0;
    height: 40px;
    font-size: 16px;
  }

  .el-main {
    padding: 0;
  }
}
</style>
