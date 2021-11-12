<template>
  <footer id="site_footer">
    <div class="container">
      <div class="button_sign-up">
        <div class="btn btn-outline">Sign-up now!</div>
      </div>
      <div class="socials">
        <div class="text">Follow Us</div>
        <div class="icons">
          <div class="icon facebook">
            <img src="../assets/img/footer-facebook.png" alt="" />
          </div>
          <div class="icon twitter">
            <img src="../assets/img/footer-twitter.png" alt="" />
          </div>
          <div class="icon youtube">
            <img src="../assets/img/footer-youtube.png" alt="" />
          </div>
          <div class="icon pinterest">
            <img src="../assets/img/footer-pinterest.png" alt="" />
          </div>
          <div class="icon periscope">
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
</script>
<style scoped lang="scss">
#site_footer {
  height: 112px;
  background-color: #303030;
  .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    .button_sign-up {
      .btn {
        border: 2px solid #0282f9;
        padding: 16px 8px;
      }
      color: white;
      text-transform: uppercase;
      font-weight: bold;
    }
    .socials {
      width: 384px;
      height: 50px;
      display: flex;
      .text {
        width: 115px;
        height: 100%;
        text-transform: uppercase;
        color: #0282f9;
        font-weight: bold;
        display: flex;
        align-items: center;
      }
      .icons {
        width: calc(100% - 115px);
        height: 100%;
        display: flex;
        .icon {
          display: flex;
          align-items: center;
          height: 100%;
          width: calc(100% / 5);
        }
      }
    }
  }
}
</style>