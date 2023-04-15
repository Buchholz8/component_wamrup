<template>
  <div id="app">
    <product-hero></product-hero>
    <product-gallery></product-gallery>
  </div>
</template>

<script>
import ProductHero from './components/ProductHero.vue'
import ProductGallery from './components/ProductGallery.vue'

export default {
  name: 'App',
  components: {
    ProductHero,
    ProductGallery
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
