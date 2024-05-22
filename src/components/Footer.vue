<template>
    <footer class="footer">
      <p>&copy; 2024 Iphone Cell. Semua hak cipta dilindungi.</p>
      <div class="social-links">
        <a href="https://facebook.com" target="_blank" aria-label="Facebook">
          <img src="/icons/facebook.svg" alt="Facebook" /> <!-- Pastikan Anda memiliki ikon Facebook di path yang benar -->
        </a>
        <a href="https://twitter.com" target="_blank" aria-label="Twitter">
          <img src="/icons/twitter.svg" alt="Twitter" />
        </a>
        <a href="https://instagram.com" target="_blank" aria-label="Instagram">
          <img src="/icons/instagram.svg" alt="Instagram" />
        </a>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #0056b3;
    color: white;
    text-align: center;
    padding: 20px;
    position: relative;
    bottom: 0;
    width: 100%;
  }
  
  .footer-content {
    margin: 0 auto;
    max-width: 1200px;
    padding: 0 20px;
  }
  
  .social-links {
    display: flex;
    justify-content: center; /* Menyelaraskan link sosial media secara horizontal */
    align-items: center; /* Menyelaraskan link sosial media secara vertikal */
    margin-top: 10px;
  }
  
  .social-links a {
    display: inline-block;
    margin: 0 10px;
  }
  
  .social-links img {
    width: 24px;
    height: 24px;
    transition: transform 0.3s ease;
  }
  
  .social-links a:hover img {
    transform: scale(1.1);
  }
  </style>