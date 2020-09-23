<template>
  <Home v-if="true" />
  <List v-else />
</template>

<script>
import Home from "./pages/Home";
import List from "./pages/List";

export default {
  name: "App",

  components: {
    Home,
    List
  },

  data: () => ({
    //
  })
};
</script>
