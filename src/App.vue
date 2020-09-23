<template>
  <el-container id="app">
    <el-header class="el-header">
      <Header />
    </el-header>
    <el-main class="el-main">

      <div>
        <div>111</div>
        <div>111</div>
        <div>111</div>
        <div>111</div>
      </div>

      <div class="block">
        <h3 class="title">账单列表</h3>
      </div>

      <div class="block">
        <h3 class="title">矿机列表</h3>
      </div>

      <el-card class="box-card">
        <div>
          <span class="number">
            {{ $t("message") }}
          </span>
          <span class="desc">
            121212
          </span>
        </div>

        <img src="./assets/img_coin.png" />
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
    height: 90px;
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
  .block {
    .title {
      font-size: 24px;
      font-family: PingFang SC;
      font-weight: bold;
      color: #343434;
    }
  }
}
</style>
