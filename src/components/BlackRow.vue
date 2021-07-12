<template>
  <div class="fluid-bg">
    <div class="container">
      <div class="custom-but">
        <a href="#">sing-up now!</a>
      </div>

      <div class="follow-us">
        follow us
        <a href="#"><img src="../assets/footer-facebook.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-twitter.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-youtube.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-pinterest.png" alt="" /></a>
        <a href="#"><img src="../assets/footer-periscope.png" alt="" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlackRow",
};
</script>

<style lang="scss" scoped>
.fluid-bg {
  background-color: #333;
  color: white;

  .container {
    display: flex;
    justify-content: space-between;
    padding: 20px 0;
    align-items: center;
    text-transform: uppercase;

    .custom-but {
      border: 2px solid #08f;
      padding: 8px 12px;
    }

    .follow-us {
      color: #08f;
      display: flex;
      align-items: center;

      img {
        width: 30px;
        margin-left: 15px;
      }
    }
  }
}
</style>