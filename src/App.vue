<template>
  <div id="app">
   
    <HelloWorld />
    <ProductList></ProductList>   <!-- this is the productList in use-->
    <h1>Hello people </h1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ProductList from './components/Product/ProductList/ProductList.vue' // we should import the Product list so we can use it,

export default {
  name: 'app',
  components: {
    HelloWorld,
    ProductList    //after import you define your component here  
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
  margin-top: 60px;
}
</style>
