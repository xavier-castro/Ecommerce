<template>
  <div id="app">
    <Header />
    <Product />
    <router-view/>
  </div>
</template>

<script>
  import Header from './components/layout/Header.vue';
  import Product from './components/Product.vue';
  export default {
    name: 'app',
    components: {
      Header,
      Product
    }
  }
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
