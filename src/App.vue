<template>
  <HeaderVue />
  <router-view />
</template>

<script>
import HeaderVue from "@/components/HeaderVue";
export default {
  name: "App",
  components: { HeaderVue },
  data() {
    return {};
  },
};
</script>


<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;
}
body {
  font-family: Arial, Helvetica, sans-serif;
}
.container {
  max-width: 1240px;
  padding: 0 15px;
  margin: 0 auto;
  width: 100%;
  height: 100%;
}
</style>
