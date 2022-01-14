<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <Product />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import Product from './components/Product.vue';

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    Product,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
