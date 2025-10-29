<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SobatNoka - Bersama Tumbuh Lebih Pintar</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {margin:0;font-family:'Poppins',sans-serif;scroll-behavior:smooth;transition:background .3s,color .3s;}
    header{position:fixed;top:0;left:0;right:0;background:#fff;z-index:1000;display:flex;justify-content:space-between;align-items:center;padding:15px 30px;box-shadow:0 2px 6px rgba(0,0,0,.1);}
    header.dark{background:#222;color:#fff;}
    header a{margin:0 10px;text-decoration:none;color:inherit;font-weight:600;}
    section{padding:100px 20px;min-height:100vh;}
center/cover no-repeat;display:flex;align-items:center;justify-content:center;flex-direction:column;color:#fff;text-align:center;}
    .hero h1{font-size:3rem;margin:0;}
    .typing{border-right:2px solid #fff;white-space:nowrap;overflow:hidden;animation:typing 4s steps(30,end) infinite alternate;}
    @keyframes typing{from{width:0}to{width:100%}}
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
    .card{background:#fff;padding:20px;border-radius:12px;box-shadow:0 4px 8px rgba(0,0,0,.1);transition:.3s;opacity:0;transform:translateY(30px);}
    .card.visible{opacity:1;transform:translateY(0);transition:all .6s ease-in-out;}
    .card:hover{transform:scale(1.05);box-shadow:0 6px 12px rgba(0,0,0,.2);}
    form{max-width:400px;margin:auto;display:flex;flex-direction:column;gap:15px;}
    input,button{padding:12px;border-radius:8px;border:1px solid #ccc;font-size:1rem;}
    button{background:#28a745;color:#fff;border:none;cursor:pointer;}
    button:hover{background:#218838;}
    footer{background:#222;color:#fff;padding:40px 20px;text-align:center;}
    .scroll-progress{position:fixed;top:0;left:0;height:5px;background:#28a745;width:0;z-index:2000;}
    #backToTop{position:fixed;bottom:30px;right:30px;background:#28a745;color:#fff;border:none;padding:12px 15px;border-radius:50%;cursor:pointer;display:none;}
    #loader{position:fixed;top:0;left:0;width:100%;height:100%;background:#fff;display:flex;justify-content:center;align-items:center;z-index:3000;}
    #loader div{border:6px solid #f3f3f3;border-top:6px solid #28a745;border-radius:50%;width:50px;height:50px;animation:spin 1s linear infinite;}
    @keyframes spin{100%{transform:rotate(360deg)}}
    body.dark{background:#111;color:#eee;}
    body.dark .card{background:#333;color:#eee;}
  </style>
</head>
<body>
  <!-- Loading Screen -->
  <div id="loader"><div></div></div>
  <!-- Scroll progress bar -->
  <div class="scroll-progress" id="scrollBar"></div>

  <!-- Header -->
  <header id="navbar">
    <div class="logo"><strong>SobatNoka</strong></div>
    <nav>
      <a href="#layanan">Layanan</a>
      <a href="#keuntungan">Keuntungan</a>
      <a href="#testimoni">Testimoni</a>
      <a href="#daftar">Daftar</a>
      <a href="#artikel">Artikel</a>
      <a href="#faq">FAQ</a>
      <a href="#kontak">Kontak</a>
      <button id="darkToggle">🌙</button>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <h1>SobatNoka</h1>
    <h2 class="typing">Bersama Tumbuh Lebih Pintar...</h2>
  </section>

  <!-- Layanan -->
  <section id="layanan">
    <h2>Layanan SobatNoka</h2>
    <div class="services">
      <div class="card">🌾 <h3>TaniPintar</h3><p>Solusi digital untuk petani agar lebih produktif dan efisien.</p></div>
      <div class="card">🔗 <h3>TaniLink</h3><p>Menghubungkan petani dengan pasar dan pembeli langsung.</p></div>
      <div class="card">🌱 <h3>BioGrow</h3><p>Pupuk organik dan bioteknologi ramah lingkungan.</p></div>
      <div class="card">🌿 <h3>BibitKu</h3><p>Penyediaan bibit unggul dan berkualitas.</p></div>
    </div>
  </section>

  <!-- Keuntungan -->
  <section id="keuntungan">
    <h2>Keuntungan Bergabung SobatNoka</h2>
    <ul>
      <li>Akses teknologi pertanian modern</li>
      <li>Jaringan pasar yang luas</li>
      <li>Bimbingan dan komunitas petani</li>
      <li>Dukungan finansial dan bibit unggul</li>
    </ul>
  </section>

  <!-- Testimoni -->
  <section id="testimoni">
    <h2>Testimoni Petani</h2>
    <blockquote>“Sejak gabung SobatNoka, hasil panen saya meningkat 2x lipat!”</blockquote>
    <cite>- Budi, Petani Cabai</cite>
  </section>

  <!-- Form Daftar -->
  <section id="daftar">
    <h2>Daftar SobatNoka Sekarang</h2>
    <form id="sobatNokaForm">
      <input type="text" name="nama" placeholder="Nama Lengkap" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="tel" name="telepon" placeholder="No. Telepon" required>
      <button type="submit">Daftar Sekarang</button>
    </form>
  </section>

  <!-- Artikel -->
  <section id="artikel">
    <h2>Artikel Terbaru</h2>
    <p>Tips pertanian, inovasi teknologi, dan cerita sukses petani bersama SobatNoka.</p>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <h2>FAQ</h2>
    <p><strong>Tanya:</strong> Apakah SobatNoka berbayar?<br><strong>Jawab:</strong> Tidak, gratis untuk semua petani.</p>
  </section>

  <!-- Footer -->
  <footer id="kontak">
    <p>🌱 SobatNoka © 2025 | Bersama Tumbuh Lebih Pintar</p>
    <p>
      <a href="#">Facebook</a> | 
      <a href="#">Instagram</a> | 
      <a href="#">YouTube</a>
    </p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!..." width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </footer>

  <button id="backToTop">⬆️</button>

  <script>
    // Loader
    window.onload=function(){document.getElementById("loader").style.display="none";};
    // Dark mode
    const toggle=document.getElementById("darkToggle");
    toggle.addEventListener("click",()=>{document.body.classList.toggle("dark");document.getElementById("navbar").classList.toggle("dark");});
    // Scroll progress
    window.onscroll=function(){
      let winScroll=document.body.scrollTop||document.documentElement.scrollTop;
      let height=document.documentElement.scrollHeight-document.documentElement.clientHeight;
      let scrolled=(winScroll/height)*100;
      document.getElementById("scrollBar").style.width=scrolled+"%";
      document.getElementById("backToTop").style.display=winScroll>200?"block":"none";
      document.querySelectorAll(".card").forEach(c=>{
        let pos=c.getBoundingClientRect().top;
        let winH=window.innerHeight;
        if(pos<winH-50){c.classList.add("visible");}
      });
    };
    // Back to top
    document.getElementById("backToTop").onclick=()=>{window.scrollTo({top:0,behavior:'smooth'});};

    // Form Google Sheets Integration
    document.getElementById("sobatNokaForm").addEventListener("submit", function(e){
      e.preventDefault();
      let data={nama:this.nama.value,email:this.email.value,telepon:this.telepon.value};
      fetch("https://script.google.com/macros/s/AKfycbyMbVgcE2OwAd-INaIIDhLHfXHqTQgwL-8jTCGUQF8kGCMxBjMUz9rVgYXR0zzxWGO6/exec",{
        method:"POST",
        body:JSON.stringify(data)
      })
      .then(res=>res.text())
      .then(res=>{
        alert("✅ Pendaftaran berhasil! Data tersimpan di Google Sheets.");
        this.reset();
      })
      .catch(err=>alert("❌ Terjadi kesalahan, coba lagi."));
    });
  </script>
  <!-- Form Daftar -->
<section id="daftar">
  <h2>Daftar SobatNoka Sekarang</h2>
  <form id="sobatNokaForm">
    <input type="text" name="nama" placeholder="Nama Lengkap" required>
    <input type="email" name="email" placeholder="Email" required>
    <input type="tel" name="telepon" placeholder="No. Telepon" required>
    <button type="submit">Daftar Sekarang</button>
  </form>
</section>

<!-- Popup Modal Sukses -->
<div id="successModal" class="popup-overlay">
  <div class="popup-box popup-success">
    <h3>✅ Pendaftaran Berhasil</h3>
    <p>Selamat bergabung bersama <b>SobatNoka</b> 🌱</p>
    <button onclick="closeModal('successModal')" class="close-btn">Tutup</button>
  </div>
</div>

<!-- Popup Modal Error -->
<div id="errorModal" class="popup-overlay">
  <div class="popup-box popup-error">
    <h3>❌ Gagal Mengirim</h3>
    <p>Terjadi kesalahan. Mohon coba lagi nanti.</p>
    <button onclick="closeModal('errorModal')" class="close-btn error-btn">Tutup</button>
  </div>
</div>

<style>
  /* Popup Overlay */
  .popup-overlay {
    display: none;
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.5);
    justify-content: center;
    align-items: center;
    z-index: 5000;
  }

  /* Popup Box */
  .popup-box {
    background: #28a745;
    color: #fff;
    padding: 30px;
    border-radius: 16px;
    text-align: center;
    max-width: 320px;
    transform: scale(0.8);
    opacity: 0;
    animation: fadeInScale 0.4s ease forwards;
  }

  .popup-error {
    background: #dc3545;
  }

  @keyframes fadeInScale {
    0% { transform: scale(0.8); opacity: 0; }
    100% { transform: scale(1); opacity: 1; }
  }

  .close-btn {
    margin-top: 15px;
    padding: 10px 20px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    background: #fff;
    color: #28a745;
    font-weight: 600;
  }

  .error-btn {
    color: #dc3545;
  }

  .close-btn:hover {
    opacity: 0.8;
  }
</style>

<script>
  // Form Google Sheets Integration + Popup Modal Animasi
  document.getElementById("sobatNokaForm").addEventListener("submit", function(e){
    e.preventDefault();
    let data={nama:this.nama.value,email:this.email.value,telepon:this.telepon.value};

    fetch("https://script.google.com/macros/s/AKfycbyMbVgcE2OwAd-INaIIDhLHfXHqTQgwL-8jTCGUQF8kGCMxBjMUz9rVgYXR0zzxWGO6/exec",{
      method:"POST",
      body:JSON.stringify(data)
    })
    .then(res=>res.text())
    .then(res=>{
      document.getElementById("successModal").style.display="flex"; // tampilkan popup sukses
      this.reset();
    })
    .catch(err=>{
      document.getElementById("errorModal").style.display="flex"; // tampilkan popup error
    });
  });

  function closeModal(id){
    document.getElementById(id).style.display="none";
  }
</script>
</body>
</html>
