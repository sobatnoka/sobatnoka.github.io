
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TaniPintar - Solusi Pintar untuk Petani Indonesia</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.6);
    }
    header p {
      font-size: 1.3rem;
      margin-top: 15px;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.6);
    }
    nav {
      background: #2E7D32;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .hero {
      text-align: center;
      margin-bottom: 50px;
    }
    .hero h2 {
      font-size: 2rem;
      color: #2E7D32;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }
    .card {
      background: #fff;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.15);
      text-align: center;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 80px;
      margin-bottom: 15px;
    }
    .card h3 {
      color: #388E3C;
      margin-bottom: 10px;
    }
    .cta {
      background: linear-gradient(to right, #4CAF50, #2E7D32);
      color: white;
      padding: 40px 20px;
      text-align: center;
      margin-top: 50px;
      border-radius: 12px;
    }
    .cta h2 {
      margin-bottom: 15px;
    }
    .cta form {
      max-width: 400px;
      margin: 20px auto 0;
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      text-align: left;
      color: #333;
    }
    .cta label {
      display: block;
      margin-bottom: 6px;
      font-weight: bold;
    }
    .cta input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    .cta button {
      background: #2E7D32;
      color: white;
      padding: 12px 28px;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      width: 100%;
    }
    .cta button:hover {
      background: #1b5e20;
    }
    footer {
      background: #2E7D32;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>TaniPintar</h1>
    <p>Solusi Pintar untuk Pertanian Indonesia</p>
  </header>

  <nav>
    <a href="#tentang">Tentang</a>
    <a href="#fitur">Fitur</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <div class="container">
    <section class="hero" id="tentang">
      <h2>Tentang TaniPintar</h2>
      <p>TaniPintar adalah platform digital yang membantu petani Indonesia dengan akses informasi, teknologi, dan pasar. Kami percaya pertanian modern harus lebih cerdas, efisien, dan menguntungkan.</p>
    </section>

    <section class="features" id="fitur">
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/2909/2909765.png" alt="Informasi">
        <h3>Informasi Pertanian</h3>
        <p>Akses data cuaca, tren harga, dan tips budidaya terkini.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/2991/2991231.png" alt="Pasar">
        <h3>Pemasaran Digital</h3>
        <p>Pasarkan hasil panen langsung ke pembeli dan mitra bisnis.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/3135/3135706.png" alt="Keuangan">
        <h3>Pembiayaan</h3>
        <p>Akses pinjaman dan layanan keuangan untuk petani.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/2965/2965567.png" alt="Komunitas">
        <h3>Komunitas</h3>
        <p>Bergabung dengan komunitas petani untuk berbagi pengalaman.</p>
      </div>
    </section>

    <section class="cta">
      <h2>Bergabung dengan TaniPintar</h2>
      <p>Wujudkan pertanian cerdas dan masa depan yang lebih baik bersama kami.</p>

      <!-- FORM PENDAFTARAN -->
      <form action="#" method="POST">
        <label for="nama">Nama Lengkap</label>
        <input type="text" id="nama" name="nama" placeholder="Masukkan nama Anda" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Masukkan email Anda" required>

        <label for="hp">Nomor HP</label>
        <input type="tel" id="hp" name="hp" placeholder="Masukkan nomor HP" required>

        <button type="submit">Daftar Sekarang</button>
      </form>
    </section>
  </div>

  <footer id="kontak">
    <p>&copy; 2025 TaniPintar | Hubungi kami: info@tanipintar.id</p>
  </footer>

</body>
</html>
