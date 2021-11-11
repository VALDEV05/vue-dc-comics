<template>
  <header id="site_header">
    <div class="container">
      <div class="logo"></div>
      <div class="nav_bar">
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#" class="active">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news</a></li>
          <li><a href="#">shop</a></li>
        </ul>
      </div>
    </div>
  </header>
</template>
<script>
/* import { defineComponent } from '@vue/composition-api' */
</script>
<style scoped lang="scss">
#site_header {
  height: 118px;
  .logo {
    height: 100%;
    width: 100px;
    background-image: url("../assets/img/dc-logo.png");
    background-position: center;
    background-repeat: no-repeat;
    float: left;
  }
  .nav_bar {
    height: 100%;
    width: 750px;
    float: right;
    display: flex;
    align-items: center;
    ul {
      list-style: none;

      li {
        display: inline;

        a {
          text-decoration: none;
          text-transform: uppercase;
          color: #464646;
          padding: 0 8px;
          font-size: 15px;
          font-weight: bold;

          &.active {
            color: #0282f9;
            border-bottom: 4px solid #0282f9;
            padding-bottom: 46px;
          }
        }
      }
    }
  }
}
</style>