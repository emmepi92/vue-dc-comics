<template>
  <div id="app">

    <Nav />
    <Main />
    <BlueRow />
    <Footer />
    <BlackRow />

  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Main from "./components/Main.vue";
import BlueRow from "./components/BlueRow.vue";
import Footer from "./components/Footer.vue";
import BlackRow from "./components/BlackRow.vue";



export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Footer,
    BlueRow,
    BlackRow
  }
}
</script>

<style lang="scss">
  @import "./style/app.scss";
</style>
