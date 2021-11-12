<template>
  <div class="card">
    <img :src="image" alt="" />
    <p>{{ series }}</p>
  </div>
</template>
<script>
export default {
  props: {
    image: String,
    series: String,
  },
};
</script>
<style lang="scss">
.card {
  height: 100%;
  width: 100%;
  p {
    text-transform: uppercase;
    font-size: 12px;
  }
}
</style>