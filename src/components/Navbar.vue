<template>
  <nav class="navbar">
    <div class="logo">Iphone Cell</div>
    <ul>
      <li>
        <a href="#home" title="Kembali ke halaman utama">Beranda</a>
      </li>
      <li>
        <a href="#products" title="Lihat produk kami">Produk</a>
      </li>
      <li>
        <a href="#about" title="Pelajari lebih lanjut tentang kami">Tentang Kami</a>
      </li>
      <li>
        <a href="#contact" title="Hubungi kami untuk informasi lebih lanjut">Kontak</a>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 50px;
  background-color: #0056b3;
  color: white;
}
.navbar .logo {
  font-size: 24px;
  font-weight: bold;
}
.navbar ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}
.navbar ul li {
  margin-left: 20px;
}
.navbar ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
  padding: 5px 10px;
}
.navbar ul li a:hover {
  background-color: #004494;
  border-radius: 5px;
}
</style>

