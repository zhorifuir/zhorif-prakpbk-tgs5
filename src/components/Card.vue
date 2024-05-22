<template>
    <div class="card">
      <img :src="product.image" alt="Gambar Produk" />
      <div class="card-body">
        <h5 class="card-title">{{ product.name }}</h5>
        <p class="card-text">{{ product.description }}</p>
        <p class="card-price">{{ product.price }}</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      product: Object
    }
  }
  </script>
  
  <style>
  .card {
    width: 300px;
    margin: 10px;
  }
  .card img {
    width: 100%;
    height: auto;
  }
  </style>