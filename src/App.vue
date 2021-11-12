<template>
  <div id="app">
    <SiteHeader />
    <!-- /#site_header -->
    <SiteMain />
    <!-- /#site_main -->
    <SiteFooter />
    <!-- /#site_footer -->
  </div>
</template>

<script>
import SiteHeader from "@/components/SiteHeader.vue";
import SiteMain from "@/components/SiteMain.vue";
import SiteFooter from "@/components/SiteFooter.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/common.scss";
</style>
