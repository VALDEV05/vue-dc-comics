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
  height: 275px;
  margin: 25px 0px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  img {
    height: 225px;
    width: 200px;
  }
  p {
    margin-top: 20px;
    text-align: left;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: bold;
  }
}
</style>