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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Greta Sans Condensed Bold", "Greta Sans Bold", Arial, sans-serif;
}
.container {
  width: 1290px;
  margin: auto;
  height: 100%;
}
</style>
