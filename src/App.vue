<template>
  <el-container id="app">
    <el-header class="el-header">
      <Header />
    </el-header>
    <el-main class="el-main">
      <el-card class="box-card">
        <div>
          <span class="number">
            {{ $t("message") }}
          </span>
          <span class="desc">
            121212
          </span>
        </div>

        <img src="./assets/img_coin@2x.png" />
      </el-card>
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
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  display: flex;
  flex: 1;
  height: 100%;
  width: 100%;
}
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
