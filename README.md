<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SobatNoka - Bersama Tumbuh Lebih Pintar</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      scroll-behavior: smooth;
    }/* Hero Section dengan Parallax */
.hero {
  height: 100vh;
  background-image: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  text-align: center;
  position: relative;
  flex-direction: column;
}
.hero h1 {
  font-size: 3rem;
  background: rgba(0, 0, 0, 0.5);
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 20px;
}
.typing-text {
  font-size: 1.5rem;
  color: #fff;
  border-right: 3px solid #fff;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  animation: typing 4s steps(40, end) forwards, blink 0.8s infinite;
}
@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}
@keyframes blink {
  0%, 100% { border-color: transparent; }
  50% { border-color: #fff; }
}

/* Animasi fade-in bergelombang */
.service-card {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeWave 1s forwards;
  background:#f9f9f9;
  padding:20px;
  border-radius:10px;
  width:200px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: pointer;
}
.service-card:nth-child(1) { animation-delay: 0.3s; }
.service-card:nth-child(2) { animation-delay: 0.6s; }
.service-card:nth-child(3) { animation-delay: 0.9s; }
.service-card:nth-child(4) { animation-delay: 1.2s; }

@keyframes fadeWave {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Hover Effect */
.service-card:hover {
  transform: translateY(-10px) scale(1.05);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
  background: #eaffea;
}

/* Scroll Reveal */
.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: all 0.8s ease;
}
.reveal.active {
  opacity: 1;
  transform: translateY(0);
}

/* Loading Screen */
#loadingScreen {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 2000;
  transition: opacity 0.5s ease;
}
.spinner {
  border: 8px solid #f3f3f3;
  border-top: 8px solid #4CAF50;
  border-radius: 50%;
  width: 60px;
  height: 60px;
  animation: spin 1s linear infinite;
}
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* Back to Top Button */
#backToTop {
  position: fixed;
  bottom: 30px;
  right: 30px;
  z-index: 999;
  background: #4CAF50;
  color: #fff;
  border: none;
  border-radius: 50%;
  padding: 15px;
  font-size: 18px;
  cursor: pointer;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  display: none;
  transition: opacity 0.3s ease;
}
#backToTop:hover {
  background: #45a049;
}

  </style>
</head>
<body>  <!-- Loading Screen -->  <div id="loadingScreen">
    <div class="spinner"></div>
  </div>  <!-- Progress bar -->  <div id="progressBar" style="position:fixed;top:0;left:0;width:0;height:5px;background:#4CAF50;z-index:1000;"></div>  <!-- Hero Section dengan Parallax dan Typing Effect -->  <section class="hero">
    <h1>Selamat Datang di SobatNoka 🌱</h1>
    <div class="typing-text">Bersama Tumbuh Lebih Pintar...</div>
  </section>  <!-- Layanan dengan animasi bergelombang dan hover -->  <section style="padding:50px;text-align:center;">
    <h2 class="reveal">Layanan SobatNoka</h2>
    <div style="display:flex;justify-content:space-around;flex-wrap:wrap;gap:20px;margin-top:30px;">
      <div class="service-card">🚜 <br/>TaniPintar</div>
      <div class="service-card">🌍 <br/>TaniLink</div>
      <div class="service-card">🌱 <br/>BioGrow</div>
      <div class="service-card">🌾 <br/>BibitKu</div>
    </div>
  </section>  <!-- Keuntungan Section -->  <section style="padding:50px;text-align:center;background:#f0f9f0;">
    <h2 class="reveal">Keuntungan Menjadi SobatNoka</h2>
    <p class="reveal">Akses mudah ke teknologi pertanian, jejaring petani, pelatihan eksklusif, dan berbagai promo menarik untuk mendukung kesejahteraan petani.</p>
  </section>  <!-- Testimoni Section -->  <section style="padding:50px;text-align:center;">
    <h2 class="reveal">Testimoni SobatNoka</h2>
    <blockquote class="reveal">“Bergabung dengan SobatNoka membuat usaha tani saya lebih produktif dan menguntungkan!” - Pak Budi</blockquote>
  </section>  <!-- Form Section -->  <section style="padding:50px;text-align:center;background:#f9f9f9;">
    <h2 class="reveal">Daftar SobatNoka</h2>
    <form class="reveal" style="display:flex;flex-direction:column;align-items:center;gap:10px;max-width:400px;margin:auto;">
      <input type="text" placeholder="Nama Lengkap" required style="padding:10px;width:100%;border-radius:5px;border:1px solid #ccc;">
      <input type="email" placeholder="Email" required style="padding:10px;width:100%;border-radius:5px;border:1px solid #ccc;">
      <input type="tel" placeholder="No. Telepon" required style="padding:10px;width:100%;border-radius:5px;border:1px solid #ccc;">
      <button type="submit" style="padding:10px 20px;background:#4CAF50;color:#fff;border:none;border-radius:5px;cursor:pointer;">Daftar</button>
    </form>
  </section>  <!-- Back to Top Button --><button id="backToTop">↑</button>

  <script>
    // Loading Screen
    window.addEventListener("load", function(){
      const loader = document.getElementById("loadingScreen");
      loader.style.opacity = "0";
      setTimeout(() => loader.style.display = "none", 500);
    });

    // Progress Bar & Back to Top
    window.onscroll = function() {
      let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
      let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
      let scrolled = (winScroll / height) * 100;
      document.getElementById("progressBar").style.width = scrolled + "%";

      const btn = document.getElementById("backToTop");
      if (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) {
        btn.style.display = "block";
      } else {
        btn.style.display = "none";
      }

      // Scroll reveal effect
      const reveals = document.querySelectorAll('.reveal');
      for (let i = 0; i < reveals.length; i++) {
        const windowHeight = window.innerHeight;
        const elementTop = reveals[i].getBoundingClientRect().top;
        const elementVisible = 100;
        if (elementTop < windowHeight - elementVisible) {
          reveals[i].classList.add("active");
        }
      }
    };

    // Back to Top click
    document.getElementById("backToTop").addEventListener("click", function(){
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script></body>
</html>
