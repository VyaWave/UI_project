<template>
  <div class="header">
    <div class="content">
      <img class="logo" src="../assets/logo.png" alt="">
      <div>账户</div>
      <div>
        <img class="language" src="../assets/icon_laug.png" alt="">
        <span class="text">语言</span>
      </div>
    </div>

  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 90px;
  background: #222832;
  .content {
    width: 1200px;
    margin: 0 auto;
    height: 90px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    div {
      display: flex;
      align-items: center;
    }
  }
  .logo {
    width: 210px;
    height: 24px;
  }
  .language {
    width: 20px;
    height: 20px;
  }
  .text {
    font-size: 18px;
    font-family: PingFang SC;
    font-weight: 500;
    color: #f5f6fa;
    margin-left: 15px;
  }
}
</style>
