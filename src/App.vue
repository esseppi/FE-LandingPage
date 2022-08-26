<template>
  <div id="app">
    <header-standard />
    <HeroStand />
    <CfirstBlockAdv />
    <DFooterPlus />
  </div>
</template>

<script>
import headerStandard from "./components/a-headerStandard.vue";
import HeroStand from "./components/b-heroStand.vue";
import CfirstBlockAdv from "./components/c-firstBlockAdv.vue";
import DFooterPlus from "./components/d-footerPlus.vue";
export default {
  components: {
    headerStandard,
    HeroStand,
    CfirstBlockAdv,
    DFooterPlus,
  },
  name: "App",
};
</script>

<style lang="scss">
@import "./assets/global.scss";
</style>
