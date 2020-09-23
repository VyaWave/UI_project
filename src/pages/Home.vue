<template>
  <div>
    <HeaderPc />
    <HeaderPhone />

    <v-card class="card" max-width="344" default>
      <div>
        <span class="number">
          111
        </span>
        <span class="desc">
          121212
        </span>
      </div>

      <img src="../assets/img_coin.png" />
    </v-card>
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
