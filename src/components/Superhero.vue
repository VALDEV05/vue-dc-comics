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
  margin: 1rem 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  img {
    height: 200px;
    width: 200px;
    margin-bottom: 20px;
  }
  p {
    text-transform: uppercase;
    font-size: 12px;
    font-weight: bold;
  }
}
</style>