<script setup>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'
import Footer from './components/Footer.vue'
import { ref } from 'vue';

const products = ref([
  { id: 1, name: 'Iphone 15 Pro max Black', description: 'RAM 512 GB', price: 'Rp22.999.000', image: './src/assets/Iphone copy.png' },
  { id: 2, name: 'Iphone 13  Pink', description: 'RAM 128 GB', price: 'Rp10.249.000', image: './src/assets/iphone2.png'},
  // Tambahkan lebih banyak produk sesuai kebutuhan
]);
</script>

<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <div class="product-container">
      <Card v-for="product in products" :key="product.id" :product="product" />
    </div>
    <Footer />
  </div>
</template>

<style>
#app {
  font-family: 'Arial', sans-serif;
}
.product-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 20px;
}
</style>

