<template>
  <div class="fluid-bg">

    <div class="container">

      <div class="content">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <div class="content-text">digital comics</div>
      </div>

      <div class="content">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <div class="content-text">dc merchandise</div>
      </div>

      <div class="content">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <div class="content-text">subscription</div>
      </div>
      
      <div class="content">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <div class="content-text">comic shop locator</div>
      </div>
      
      <div class="content">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <div class="content-text">dc power visa</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlueRow",
};
</script>


<style lang="scss" scoped>
.fluid-bg {
  background-color: #18f;
  padding: 40px 20px;
  .container {
    display: flex;
    justify-content: space-around;
    .content {
      text-transform: uppercase;
      color: white;
      display: flex;
      align-items: center;

      img {
        max-height: 40px;
        max-width: 40px;
        margin-right: 10px;
      }
    }
  }
}
</style>