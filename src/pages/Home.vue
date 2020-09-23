<template>
  <div>
    <HeaderPc />
    <HeaderPhone />

  </div>
</template>

<script>
import HeaderPc from "../components/header_pc";
import HeaderPhone from "../components/header_phone";

export default {
  name: "home",

  components: {
    HeaderPc,
    HeaderPhone
  },

  data: () => ({
    //
  })
};
</script>

<style lang="scss" scoped>
.card {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
