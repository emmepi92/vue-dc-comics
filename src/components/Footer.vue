<template>
  <div class="fluid-bg">
    <div class="container">
      <div class="list-container">
        <div class="list-content">
          <ul>
            <li>DC COMICS</li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul>
            <li>DC SHOP</li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div class="list-content">
          <ul>
            <li>DC</li>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div class="list-content">
          <ul>
            <li>SITES</li>
            <li><a href="#">DC</a></li>
            <li><a href="#">DC UNIVERSE INFINITE</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Shop</a></li>
            <li><a href="#">MAD Magazine</a></li>
          </ul>
        </div>
      </div>

      <img src="../assets/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>


<style lang="scss" scoped>
.fluid-bg {
  background-image: url("../assets/footer-bg.jpg");
  color: white;

  .container {
      display: flex;
      justify-content: space-between;
      position: relative;
      overflow: hidden;

    .list-container {
      display: flex;

      .list-content {
        padding-right: 20px;

        ul {
          padding-bottom: 20px;

          li {
            font-weight: 200;
            &:first-child {
              font-weight: bold;
              margin: 20px 0;
            }
          }
        }
      }
    }

    img {
        position: absolute;
        right: 0;
        top: -25%;

    }
  }
}
</style>