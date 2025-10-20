
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SobatNoka - Bersama Majukan Pertanian</title>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif;}
    body {background: #f9f9f9; color: #333; line-height: 1.6;}
    header {background: linear-gradient(135deg,#4CAF50,#2E7D32); color: white; padding: 50px 20px; text-align: center;}
    header h1 {font-size: 2.5em; margin-bottom: 10px; animation: fadeIn 2s;}
    header p {font-size: 1.2em; animation: fadeIn 3s;}.container {width: 90%; max-width: 1100px; margin: auto; padding: 40px 20px;}
.section-title {text-align: center; margin-bottom: 30px; font-size: 2em; color: #2E7D32;}

.services {display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px;}
.card {background: white; padding: 20px; border-radius: 12px; text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s ease, box-shadow 0.3s ease; opacity:0; transform: translateY(30px);}
.card:hover {transform: scale(1.05); box-shadow: 0 8px 16px rgba(0,0,0,0.2);}
.card img {width: 60px; margin-bottom: 15px;}

.benefits ul {list-style: none; text-align: center;}
.benefits ul li {margin: 10px 0; padding: 10px; background: #e8f5e9; border-radius: 8px;}

.form-section {background: #fff; padding: 30px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); max-width: 500px; margin: auto; opacity:0; transform: translateY(30px);}
form input, form button {width: 100%; padding: 12px; margin: 10px 0; border-radius: 8px; border: 1px solid #ccc;}
form button {background: #4CAF50; color: white; border: none; cursor: pointer; font-size: 1em; transition: 0.3s;}
form button:hover {background: #388E3C;}

.testimonials {display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px;}
.testimonial-card {background: white; padding: 20px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); font-style: italic; opacity:0; transform: translateY(30px);}
.testimonial-card h4 {margin-top: 15px; color: #2E7D32; font-style: normal;}

.faq {max-width: 800px; margin: auto;}
.faq-item {background: white; padding: 15px; margin-bottom: 10px; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); cursor: pointer;}
.faq-item h3 {font-size: 1.1em; color: #2E7D32;}
.faq-item p {display: none; margin-top: 10px;}

.blog {display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px;}
.blog-card {background: white; padding: 20px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: 0.3s; opacity:0; transform: translateY(30px);}
.blog-card:hover {transform: scale(1.03);}
.blog-card h3 {color: #2E7D32; margin-bottom: 10px;}

.newsletter {background: #fff; padding: 30px; border-radius: 12px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); max-width: 600px; margin: auto; text-align: center; opacity:0; transform: translateY(30px);}
.newsletter input {width: 70%; padding: 12px; border-radius: 8px 0 0 8px; border: 1px solid #ccc; outline: none;}
.newsletter button {width: 30%; padding: 12px; border-radius: 0 8px 8px 0; border: none; background: #4CAF50; color: white; cursor: pointer;}
.newsletter button:hover {background: #388E3C;}

footer {background: #2E7D32; color: white; text-align: center; padding: 20px; margin-top: 40px;}

.wa-btn {display: block; text-align: center; margin: 20px auto; padding: 12px 20px; background: #25D366; color: white; font-weight: bold; border-radius: 8px; text-decoration: none; max-width: 250px; transition: 0.3s;}
.wa-btn:hover {background: #1ebe5d;}

/* Animations */
@keyframes fadeIn {from {opacity: 0;} to {opacity: 1;}}
.show {opacity: 1 !important; transform: translateY(0) !important; transition: all 1s ease;}

  </style>
</head>
<body>
  <header>
    <h1>SobatNoka</h1>
    <p>Bersama Majukan Pertanian, Peternakan, dan Perikanan Indonesia</p>
  </header>  <section class="container services-section">
    <h2 class="section-title">Layanan SobatNoka</h2>
    <div class="services">
      <div class="card"><img src="https://img.icons8.com/color/96/tractor.png" alt="TaniPintar"><h3>TaniPintar</h3><p>Platform edukasi pintar untuk meningkatkan keterampilan petani.</p></div>
      <div class="card"><img src="https://img.icons8.com/color/96/network.png" alt="TaniLink"><h3>TaniLink</h3><p>Menghubungkan petani, pembeli, dan mitra dalam satu ekosistem.</p></div>
      <div class="card"><img src="https://img.icons8.com/color/96/plant-under-sun.png" alt="BioGrow"><h3>BioGrow</h3><p>Solusi ramah lingkungan untuk meningkatkan hasil panen.</p></div>
      <div class="card"><img src="https://img.icons8.com/color/96/seed-of-life.png" alt="BibitKu"><h3>BibitKu</h3><p>Penyedia bibit unggul yang terjamin kualitasnya.</p></div>
    </div>
  </section>  <section class="container benefits">
    <h2 class="section-title">Keuntungan Menjadi SobatNoka</h2>
    <ul>
      <li>Akses ke teknologi dan edukasi pertanian modern</li>
      <li>Jaringan mitra dan pasar yang luas</li>
      <li>Dukungan inovasi berkelanjutan</li>
      <li>Kesempatan mendapatkan pendanaan dan investasi</li>
    </ul>
  </section>  <section class="container testimonials-section">
    <h2 class="section-title">Testimoni SobatNoka</h2>
    <div class="testimonials">
      <div class="testimonial-card">
        <p>“Sejak bergabung dengan SobatNoka, hasil panen saya meningkat pesat. Edukasi dari TaniPintar sangat membantu.”</p>
        <h4>– Budi, Petani Cabe</h4>
      </div>
      <div class="testimonial-card">
        <p>“TaniLink membuat saya lebih mudah menjual hasil panen langsung ke pembeli tanpa perantara.”</p>
        <h4>– Sari, Petani Bawang Merah</h4>
      </div>
      <div class="testimonial-card">
        <p>“BibitKu benar-benar menyediakan bibit unggul. Tanaman saya tumbuh sehat dan kuat.”</p>
        <h4>– Joko, Petani Padi</h4>
      </div>
    </div>
  </section>  <section class="container form-section">
    <h2 class="section-title">Daftar SobatNoka</h2>
    <form>
      <input type="text" placeholder="Nama Lengkap" required>
      <input type="email" placeholder="Email" required>
      <input type="tel" placeholder="No. Telepon" required>
      <button type="submit">Daftar Sekarang</button>
    </form>
    <a href="https://wa.me/6281234567890" target="_blank" class="wa-btn">💬 Chat Admin via WhatsApp</a>
  </section>  <section class="container faq-section">
    <h2 class="section-title">FAQ (Pertanyaan yang Sering Diajukan)</h2>
    <div class="faq">
      <div class="faq-item"><h3>Apa itu SobatNoka?</h3><p>SobatNoka adalah komunitas digital yang mendukung petani, peternak, dan pembudidaya dalam meningkatkan produktivitas.</p></div>
      <div class="faq-item"><h3>Bagaimana cara bergabung?</h3><p>Cukup daftar melalui form pendaftaran atau hubungi admin via WhatsApp.</p></div>
      <div class="faq-item"><h3>Apakah SobatNoka berbayar?</h3><p>Saat ini SobatNoka gratis, dengan beberapa layanan premium di masa depan.</p></div>
    </div>
  </section>  <section class="container blog-section">
    <h2 class="section-title">Artikel & Edukasi Pertanian</h2>
    <div class="blog">
      <div class="blog-card">
        <h3>5 Tips Meningkatkan Hasil Panen Cabe</h3>
        <p>Pahami cara pemilihan bibit unggul, teknik pemupukan, hingga pengendalian hama agar hasil lebih maksimal.</p>
      </div>
      <div class="blog-card">
        <h3>Urban Farming: Solusi Pertanian di Perkotaan</h3>
        <p>Mengenal tren pertanian modern di lahan sempit dengan teknik hidroponik dan vertikultur.</p>
      </div>
      <div class="blog-card">
        <h3>Peran Teknologi dalam Pertanian Masa Depan</h3>
        <p>Dari IoT hingga AI, teknologi kini menjadi sahabat petani untuk meningkatkan efisiensi dan produktivitas.</p>
      </div>
    </div>
  </section>  <section class="container newsletter-section">
    <h2 class="section-title">Berlangganan Newsletter SobatNoka</h2>
    <div class="newsletter">
      <p>Dapatkan update terbaru seputar pertanian, teknologi, dan peluang SobatNoka langsung ke email Anda.</p>
      <form>
        <input type="email" placeholder="Masukkan email Anda" required>
        <button type="submit">Subscribe</button>
      </form>
    </div>
  </section>  <footer>
    <p>&copy; 2025 SobatNoka. Semua Hak Dilindungi.</p>
  </footer>  <script>
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if(entry.isIntersecting){ entry.target.classList.add('show'); }
      });
    }, {threshold: 0.2});

    document.querySelectorAll('.card, .form-section, .testimonial-card, .blog-card, .newsletter').forEach(el => observer.observe(el));

    document.querySelectorAll('.faq-item').forEach(item => {
      item.addEventListener('click', () => {
        const p = item.querySelector('p');
        p.style.display = p.style.display === 'block' ? 'none' : 'block';
      });
    });
  </script></bscript>
