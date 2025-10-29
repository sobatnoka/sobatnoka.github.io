<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SobatNoka 🌾 | Bersama Membangun Pertanian Modern</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: #f9fff9;
      color: #333;
    }

    /* === HEADER === */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #28a745;
      color: #fff;
      padding: 12px 20px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      transition: top 0.4s ease;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
    }

    .nav-links {
      display: flex;
      gap: 20px;
    }

    .nav-links a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
    }

    .menu-toggle {
      display: none;
      font-size: 24px;
      background: none;
      border: none;
      color: #fff;
      cursor: pointer;
    }

    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 60px;
        right: 15px;
        background: #28a745;
        border-radius: 10px;
        padding: 10px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      }

      .nav-links.active {
        display: flex;
        animation: fadeInMenu 0.3s ease forwards;
      }

      @keyframes fadeInMenu {
        from { opacity: 0; transform: translateY(-10px); }
        to { opacity: 1; transform: translateY(0); }
      }

      .menu-toggle {
        display: block;
      }
    }

    /* === HERO === */
    section {
      padding: 80px 20px;
      text-align: center;
    }

    #home {
      background: linear-gradient(135deg, #28a745, #85e085);
      color: white;
      padding-top: 120px;
      padding-bottom: 120px;
    }

    h1 {
      font-size: 36px;
    }

    h2 {
      color: #28a745;
      font-size: 28px;
    }

    /* === PRODUK === */
    .produk-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .produk-card {
      background: white;
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .produk-card:hover {
      transform: translateY(-5px);
    }

    /* === KEUNTUNGAN === */
    ul {
      list-style: none;
      padding: 0;
      max-width: 600px;
      margin: 20px auto;
      text-align: left;
    }

    ul li {
      background: #e8ffe8;
      margin: 10px 0;
      padding: 10px 15px;
      border-radius: 10px;
    }

    /* === VIDEO SECTION === */
    .video-section {
      text-align: center;
      padding: 60px 20px;
      background: #f8fff8;
    }

    .video-container {
      max-width: 800px;
      margin: 0 auto;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    .video-container video {
      width: 100%;
      height: auto;
      display: block;
    }

    /* === FORM === */
    form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      max-width: 400px;
      margin: 0 auto;
    }

    input, button {
      width: 100%;
      padding: 10px;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    button {
      background: #28a745;
      color: white;
      font-weight: bold;
      border: none;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #218838;
    }

    /* === POPUP === */
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
  </style>
</head>

<body>
  <!-- HEADER -->
  <header class="navbar" id="navbar">
    <div class="logo">🌾 <b>SobatNoka</b></div>
    <button class="menu-toggle" id="menuToggle">☰</button>
    <nav id="navMenu" class="nav-links">
      <a href="#home">Beranda</a>
      <a href="#produk">Produk</a>
      <a href="#keuntungan">Keuntungan</a>
      <a href="#daftar">Daftar</a>
    </nav>
  </header>

  <!-- HERO -->
  <section id="home">
    <h1>Selamat Datang di SobatNoka 🌱</h1>
    <p>Bersama membangun pertanian modern dengan solusi digital terintegrasi.</p>
  </section>

  <!-- PRODUK -->
  <section id="produk">
    <h2>Produk SobatNoka</h2>
    <div class="produk-grid">
      <div class="produk-card"><h3>TaniPintar</h3><p>Solusi digital cerdas untuk pertanian presisi.</p></div>
      <div class="produk-card"><h3>TaniLink</h3><p>Konektivitas antar pelaku agribisnis dengan efisien.</p></div>
      <div class="produk-card"><h3>BioGrow</h3><p>Pupuk organik modern berbasis bioteknologi.</p></div>
      <div class="produk-card"><h3>BibitKu</h3><p>Pusat distribusi benih dan bibit unggul untuk petani.</p></div>
    </div>
  </section>

  <!-- KEUNTUNGAN -->
  <section id="keuntungan">
    <h2>Keuntungan Menjadi SobatNoka</h2>
    <ul>
      <li>🌿 Akses pelatihan dan teknologi pertanian terbaru</li>
      <li>🤝 Terhubung dengan komunitas petani modern</li>
      <li>💰 Akses modal dan pasar lebih mudah</li>
      <li>📊 Data dan insight untuk meningkatkan hasil panen</li>
    </ul>
  </section>

  <!-- VIDEO -->
  <section id="video" class="video-section">
    <h2>Kenali SobatNoka Lebih Dekat 🎥</h2>
    <p>Tonton video singkat tentang bagaimana SobatNoka membantu petani dan ekosistem pertanian modern.</p>
    <div class="video-container">
      <video controls autoplay muted loop>
        <source src="https://raw.githubusercontent.com/sobatnoka/sobatnoka.github.io/3a3335eb1f203eef80cb271ce8adca74f329d758/f03b0fd5d784e018fbde2b67eaad6ce2_1761736116714.mp4" type="video/mp4">
        Browser kamu tidak mendukung video.
      </video>
    </div>
  </section>

  <!-- FORM PENDAFTARAN -->
  <section id="daftar">
    <h2>Daftar SobatNoka Sekarang</h2>
    <form id="sobatNokaForm">
      <input type="text" name="nama" placeholder="Nama Lengkap" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="tel" name="telepon" placeholder="No. Telepon" required>
      <button type="submit">Daftar Sekarang</button>
    </form>
  </section>

  <!-- POPUP -->
  <div id="successModal" class="popup-overlay">
    <div class="popup-box">
      <h3>✅ Pendaftaran Berhasil</h3>
      <p>Selamat bergabung bersama <b>SobatNoka</b> 🌱</p>
      <button onclick="closeModal('successModal')" class="close-btn">Tutup</button>
    </div>
  </div>

  <div id="errorModal" class="popup-overlay">
    <div class="popup-box popup-error">
      <h3>❌ Gagal Mengirim</h3>
      <p>Terjadi kesalahan. Mohon coba lagi nanti.</p>
      <button onclick="closeModal('errorModal')" class="close-btn error-btn">Tutup</button>
    </div>
  </div>

  <script>
    // MENU MOBILE
    const menuToggle = document.getElementById("menuToggle");
    const navMenu = document.getElementById("navMenu");
    const navbar = document.getElementById("navbar");

    menuToggle.addEventListener("click", () => {
      navMenu.classList.toggle("active");
    });

    // AUTO HIDE HEADER
    let lastScrollTop = 0;
    window.addEventListener("scroll", () => {
      const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
      if (scrollTop > lastScrollTop && scrollTop > 60) navbar.style.top = "-80px";
      else navbar.style.top = "0";
      lastScrollTop = scrollTop <= 0 ? 0 : scrollTop;
    });

    // FORM GOOGLE SHEETS
    document.getElementById("sobatNokaForm").addEventListener("submit", function(e){
      e.preventDefault();
      let data={nama:this.nama.value,email:this.email.value,telepon:this.telepon.value};

      fetch("https://script.google.com/macros/s/AKfycbyMbVgcE2OwAd-INaIIDhLHfXHqTQgwL-8jTCGUQF8kGCMxBjMUz9rVgYXR0zzxWGO6/exec",{
        method:"POST",
        body:JSON.stringify(data)
      })
      .then(res=>res.text())
      .then(res=>{
        document.getElementById("successModal").style.display="flex";
        this.reset();
      })
      .catch(err=>{
        document.getElementById("errorModal").style.display="flex";
      });
    });

    function closeModal(id){
      document.getElementById(id).style.display="none";
    }
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kuis Edukasi Pertanian 🌾</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to bottom right, #8bc34a, #558b2f);
      color: #fff;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 500px;
      margin: 50px auto;
      background: rgba(0, 0, 0, 0.25);
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    button {
      background: #33691e;
      color: #fff;
      border: none;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #689f38;
    }
    select {
      padding: 8px;
      border-radius: 8px;
      border: none;
      margin-bottom: 20px;
    }
    .leaderboard {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      padding: 10px;
      margin-top: 20px;
    }
    .timer {
      font-size: 20px;
      background: rgba(0, 0, 0, 0.3);
      padding: 8px 15px;
      display: inline-block;
      border-radius: 10px;
      margin-bottom: 10px;
    }
    h1, h2, h3 {
      margin-bottom: 15px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🌾 Kuis Edukasi Pertanian</h1>

    <div id="category-container">
      <h2>Pilih Kategori</h2>
      <select id="categorySelect">
        <option value="">-- Pilih Kategori --</option>
        <option value="tanaman">🌱 Tanaman</option>
        <option value="peternakan">🐄 Peternakan</option>
        <option value="perikanan">🐟 Perikanan</option>
        <option value="hortikultura">🌼 Hortikultura</option>
      </select><br />
      <button onclick="startCategory()">Mulai Kuis</button>
    </div>

    <div id="quiz-container" style="display: none">
      <div class="timer">⏳ Waktu: <span id="time">20</span> detik</div>
      <h2 id="question"></h2>
      <button onclick="answer(true)">Benar</button>
      <button onclick="answer(false)">Salah</button>
    </div>

    <div id="result" style="display: none">
      <h2>Skor Akhir: <span id="score"></span></h2>
      <button onclick="restartQuiz()">Ulangi</button>
      <button id="shareBtn">📲 Bagikan ke WhatsApp</button>
    </div>

    <div class="leaderboard" id="leaderboard" style="display: none">
      <h3>🏆 Papan Peringkat <span id="categoryName"></span></h3>
      <ul id="leaderList"></ul>
    </div>
  </div>

  <script>
    const allQuestions = {
      tanaman: [
        { text: "Padi adalah tanaman pangan utama di Indonesia.", correct: true },
        { text: "Jagung termasuk tanaman hortikultura.", correct: false },
        { text: "Tanaman kedelai memerlukan lahan yang tergenang air.", correct: false },
        { text: "Pupuk NPK mengandung unsur Nitrogen, Fosfor, dan Kalium.", correct: true },
        { text: "Tebu digunakan untuk menghasilkan gula.", correct: true },
        { text: "Singkong termasuk tanaman buah.", correct: false }
      ],
      peternakan: [
        { text: "Sapi merupakan hewan ruminansia.", correct: true },
        { text: "Ayam termasuk hewan herbivora.", correct: false },
        { text: "Kambing tidak bisa mencerna rumput.", correct: false },
        { text: "Peternakan modern menggunakan sistem kandang tertutup (closed house).", correct: true },
        { text: "Susu sapi tidak mengandung protein.", correct: false },
        { text: "Ayam pedaging disebut broiler.", correct: true }
      ],
      perikanan: [
        { text: "Ikan lele hidup di air asin.", correct: false },
        { text: "Udang vaname termasuk jenis udang air laut.", correct: true },
        { text: "Kolam terpal bisa digunakan untuk budidaya ikan nila.", correct: true },
        { text: "Pakan ikan harus mengandung protein tinggi.", correct: true },
        { text: "Aerator digunakan untuk meningkatkan oksigen dalam air.", correct: true },
        { text: "Tambak udang hanya bisa dibuat di pegunungan.", correct: false }
      ],
      hortikultura: [
        { text: "Cabai, tomat, dan bawang termasuk tanaman hortikultura.", correct: true },
        { text: "Mangga termasuk tanaman semusim.", correct: false },
        { text: "Sayuran daun termasuk kelompok tanaman hortikultura.", correct: true },
        { text: "Pupuk kandang tidak boleh digunakan untuk tanaman hortikultura.", correct: false },
        { text: "Hortikultura mencakup tanaman buah, sayur, dan bunga.", correct: true },
        { text: "Kentang termasuk tanaman serealia.", correct: false }
      ]
    };

    let current = 0;
    let score = 0;
    let selectedCategory = "";
    let questions = [];
    let timer;
    let timeLeft = 20;

    function shuffle(array) {
      return array.sort(() => Math.random() - 0.5);
    }

    function startCategory() {
      const category = document.getElementById("categorySelect").value;
      if (!category) return alert("Pilih kategori dulu!");
      selectedCategory = category;
      questions = shuffle([...allQuestions[category]]).slice(0, 5);
      document.getElementById("category-container").style.display = "none";
      document.getElementById("quiz-container").style.display = "block";
      document.getElementById("leaderboard").style.display = "block";
      document.getElementById("categoryName").textContent = category.toUpperCase();
      showQuestion();
      renderLeaderboard();
    }

    function startTimer() {
      clearInterval(timer);
      timeLeft = 20;
      document.getElementById("time").textContent = timeLeft;
      timer = setInterval(() => {
        timeLeft--;
        document.getElementById("time").textContent = timeLeft;
        if (timeLeft <= 0) {
          clearInterval(timer);
          current++;
          showQuestion();
        }
      }, 1000);
    }

    function showQuestion() {
      if (current < questions.length) {
        document.getElementById("question").textContent = questions[current].text;
        startTimer();
      } else {
        clearInterval(timer);
        endQuiz();
      }
    }

    function answer(choice) {
      if (choice === questions[current].correct) score++;
      current++;
      clearInterval(timer);
      showQuestion();
    }

    function endQuiz() {
      document.getElementById("quiz-container").style.display = "none";
      document.getElementById("result").style.display = "block";
      document.getElementById("score").textContent = `${score} / ${questions.length}`;
      const name = prompt("Masukkan nama kamu untuk papan peringkat:");
      if (name) {
        const leaderboardKey = `leaderboard_${selectedCategory}`;
        const leaderboard = JSON.parse(localStorage.getItem(leaderboardKey) || "[]");
        leaderboard.push({ name, score });
        leaderboard.sort((a, b) => b.score - a.score);
        localStorage.setItem(leaderboardKey, JSON.stringify(leaderboard));
      }
      renderLeaderboard();

      // Tombol share
      document.getElementById("shareBtn").onclick = () => {
        const text = `Aku baru dapat skor ${score}/${questions.length} di Kuis Edukasi Pertanian 🌾 kategori ${selectedCategory.toUpperCase()}! Coba kamu juga!`;
        const url = `https://api.whatsapp.com/send?text=${encodeURIComponent(text)}`;
        window.open(url, "_blank");
      };
    }

    function restartQuiz() {
      current = 0;
      score = 0;
      questions = shuffle([...allQuestions[selectedCategory]]).slice(0, 5);
      document.getElementById("result").style.display = "none";
      document.getElementById("quiz-container").style.display = "block";
      showQuestion();
    }

    function renderLeaderboard() {
      const leaderboardKey = `leaderboard_${selectedCategory}`;
      const leaderboard = JSON.parse(localStorage.getItem(leaderboardKey) || "[]");
      document.getElementById("leaderList").innerHTML = leaderboard
        .slice(0, 5)
        .map(p => `<li>${p.name} - ${p.score} poin</li>`)
        .join("");
    }
  </script>
</body>
</html>


<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SobatNoka - Bersama Tumbuh Lebih Pintar</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {margin:0;font-family:'Poppins',sans-serif;scroll-behavior:smooth;transition:background .3s,color .3s;}
    header{position:fixed;top:0;left:0;right:0;background:#fff;z-index:1000;display:flex;justify-content:space-between;align-items:center;padding:15px 30px;box-shadow:0 2px 6px rgba(0,0,0,.1);}
 /* === Header Umum === */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #28a745;
  color: #fff;
  padding: 12px 20px;
  position: sticky;
  top: 0;
  z-index: 1000;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

.logo {
  font-size: 20px;
  font-weight: bold;
}

/* === Menu Desktop === */
.nav-links {
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.2s;
}

.nav-links a:hover {
  color: #d4ffd6;
}

/* === Tombol Menu (HP) === */
.menu-toggle {
  display: none;
  font-size: 24px;
  background: none;
  border: none;
  color: #fff;
  cursor: pointer;
}

/* === Mode Mobile === */
@media (max-width: 768px) {
  .nav-links {
    display: none; /* sembunyikan menu */
    flex-direction: column;
    position: absolute;
    top: 60px;
    right: 15px;
    background: #28a745;
    border-radius: 10px;
    padding: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  }

  .nav-links a {
    padding: 10px;
    border-bottom: 1px solid rgba(255,255,255,0.3);
  }

  .nav-links a:last-child {
    border-bottom: none;
  }

  .menu-toggle {
    display: block; /* tampilkan tombol menu */
  }

  /* Saat aktif */
  .nav-links.active {
    display: flex;
    animation: fadeInMenu 0.3s ease forwards;
  }

  @keyframes fadeInMenu {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
  }
}   header.dark{background:#222;color:#fff;}
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
  <script>
  // Toggle menu di layar kecil
  const menuToggle = document.getElementById("menuToggle");
  const navMenu = document.getElementById("navMenu");

  menuToggle.addEventListener("click", () => {
    navMenu.classList.toggle("active");
  });
</script>
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
