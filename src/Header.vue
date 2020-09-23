<template>
  <div class="box">
    <HeaderPc />
    <!-- <HeaderPhone /> -->
  </div>
</template>

<script>
import HeaderPc from "./components/header_pc";
// import HeaderPhone from "./components/header_phone";
export default {
  components: {
    HeaderPc
    // HeaderPhone
  }
};
</script>

<style lang="scss" scoped>
.box {
  background: #212832;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
