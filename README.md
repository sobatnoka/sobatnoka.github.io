<!doctype html>

<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TaniPintar — Kelas Online Bertani Cerdas</title>
  <meta name="description" content="Dari Lahan Kosong Jadi Ladang Emas — Belajar Bertani Cerdas Bersama TaniPintar. Kelas online interaktif pertanian, peternakan, dan perikanan budidaya." />
  <meta property="og:title" content="TaniPintar — Kelas Online Bertani Cerdas" />
  <meta property="og:description" content="Belajar bertani modern dengan praktisi lapangan. Video, e-book, simulasi, dan magang." />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=TaniPintar" />
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    /* Simple hero gradient overlay and small UI tweaks */
    .hero-bg{background-image: linear-gradient(180deg, rgba(4,120,87,0.9), rgba(16,185,129,0.85)), url('https://via.placeholder.com/1600x900.png?text=Pertanian'); background-size: cover; background-position: center;}
    .glass{backdrop-filter: blur(6px); background: rgba(255,255,255,0.6);}    
    @media (prefers-reduced-motion: no-preference){
      .float-up{transform: translateY(12px); animation: floatUp 1.2s ease-out forwards;}
      @keyframes floatUp{to{transform: translateY(0); opacity:1}}
    }
  </style>
</head>
<body class="antialiased text-gray-800 bg-gray-50">
  <!-- NAV -->
  <header class="w-full bg-white shadow">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <a href="#" class="flex items-center gap-3">
        <img src="https://via.placeholder.com/48x48.png?text=TP" alt="TaniPintar" class="w-10 h-10 rounded-md" />
        <div>
          <h1 class="font-bold text-lg">TaniPintar</h1>
          <p class="text-xs text-green-600">Belajar Bertani Cerdas</p>
        </div>
      </a>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#agenda" class="hover:text-green-600">Agenda</a>
        <a href="#program" class="hover:text-green-600">Program</a>
        <a href="#instruktur" class="hover:text-green-600">Instruktur</a>
        <a href="#pricing" class="hover:text-green-600">Harga</a>
        <a href="#faq" class="hover:text-green-600">FAQ</a>
        <a href="#daftar" class="ml-3 inline-block bg-green-600 text-white px-4 py-2 rounded-lg shadow">Daftar Sekarang</a>
      </nav>
      <button class="md:hidden p-2 rounded-md text-gray-700" aria-label="menu" onclick="document.getElementById('mobile').classList.toggle('hidden')">☰</button>
    </div>
    <div id="mobile" class="md:hidden hidden px-6 pb-4">
      <a href="#agenda" class="block py-2">Agenda</a>
      <a href="#program" class="block py-2">Program</a>
      <a href="#instruktur" class="block py-2">Instruktur</a>
      <a href="#pricing" class="block py-2">Harga</a>
      <a href="#faq" class="block py-2">FAQ</a>
    </div>
  </header>  <!-- HERO -->  <section class="hero-bg text-white">
    <div class="max-w-6xl mx-auto px-6 py-20 flex flex-col lg:flex-row items-center gap-12">
      <div class="lg:w-1/2">
        <span class="inline-block bg-white bg-opacity-20 px-3 py-1 rounded-full text-sm">Kelas Online • Interaktif • Sertifikat</span>
        <h2 class="mt-6 text-4xl lg:text-5xl font-extrabold leading-tight">Pengen bisa bertani?<br class="hidden md:block"> Yuk belajar bersama <span class="text-green-200">TaniPintar</span></h2>
        <p class="mt-4 text-lg text-green-50/90">Dari lahan kosong jadi ladang emas — pelajari teknik pertanian, peternakan & perikanan budidaya dengan praktisi. Modul video, e-book, diskusi, dan praktik nyata.</p>
        <div class="mt-6 flex items-center gap-4">
          <a href="#daftar" class="inline-block bg-white text-green-700 font-semibold px-6 py-3 rounded-lg shadow-lg">Daftar Sekarang</a>
          <a href="#program" class="inline-block border border-white px-5 py-3 rounded-lg">Lihat Program</a>
        </div>
        <div class="mt-6 text-sm text-green-100">Kuota terbatas — Periode pendaftaran: <strong>1–30 November 2025</strong></div>
      </div><div class="lg:w-1/2">
    <div class="bg-white rounded-2xl overflow-hidden shadow-2xl float-up">
      <img src="https://via.placeholder.com/720x420.png?text=Video+Preview" alt="Preview" class="w-full h-64 object-cover">
      <div class="p-4">
        <h3 class="font-bold">Preview Kelas: Teknik Tanam & Irigasi Hemat</h3>
        <p class="text-sm mt-2 text-gray-600">Video pendek & ringkasan modul. Tonton cuplikan materi untuk melihat kualitas pembelajaran.</p>
        <div class="mt-3 flex gap-3">
          <a href="#" class="text-sm text-green-700 font-semibold">Tonton Cuplikan</a>
          <a href="#" class="text-sm text-gray-500">Lihat Silabus</a>
        </div>
      </div>
    </div>
  </div>
</div>

  </section>  <!-- TRUST BAR -->  <section class="max-w-6xl mx-auto px-6 py-8">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center text-sm text-gray-600">
      <div class="p-4 bg-white rounded-lg shadow"><strong>+2000</strong><div>Peserta Terdaftar</div></div>
      <div class="p-4 bg-white rounded-lg shadow"><strong>30+</strong><div>Instruktur Praktisi</div></div>
      <div class="p-4 bg-white rounded-lg shadow"><strong>90%</strong><div>Peserta Puas</div></div>
      <div class="p-4 bg-white rounded-lg shadow"><strong>Magang</strong><div>Kesempatan di Mitra</div></div>
    </div>
  </section>  <!-- PROGRAM -->  <section id="program" class="max-w-6xl mx-auto px-6 py-12">
    <div class="grid lg:grid-cols-3 gap-8">
      <div class="bg-white rounded-xl p-6 shadow-md">
        <h3 class="font-bold text-xl">Kelas Dasar Bertani Cerdas</h3>
        <p class="mt-3 text-sm text-gray-600">Mulai dari nol: jenis tanah, pemilihan benih, pupuk organik, pengairan, dan praktik kebun kecil.</p>
        <ul class="mt-4 text-sm space-y-2 text-gray-700">
          <li>• Modul video + e-book</li>
          <li>• Praktik lapangan & proyek akhir</li>
          <li>• Sertifikat digital</li>
        </ul>
      </div><div class="bg-white rounded-xl p-6 shadow-md">
    <h3 class="font-bold text-xl">Kelas Peternakan Pintar</h3>
    <p class="mt-3 text-sm text-gray-600">Kesehatan ternak, manajemen pakan efisien, dan cara meningkatkan produktivitas.</p>
    <ul class="mt-4 text-sm space-y-2 text-gray-700">
      <li>• Studi kasus peternakan skala kecil</li>
      <li>• Panduan pakan & sanitasi</li>
      <li>• Sesi tanya jawab langsung</li>
    </ul>
  </div>

  <div class="bg-white rounded-xl p-6 shadow-md">
    <h3 class="font-bold text-xl">Kelas Perikanan Budidaya</h3>
    <p class="mt-3 text-sm text-gray-600">Budidaya lele, nila, & udang vaname — teknik kolam & sistem modern.</p>
    <ul class="mt-4 text-sm space-y-2 text-gray-700">
      <li>• Teknis pemeliharaan & nutrisi</li>
      <li>• Monitoring kualitas air</li>
      <li>• Pendampingan teknis</li>
    </ul>
  </div>
</div>

  </section>  <!-- AGENDA / SCHEDULE -->  <section id="agenda" class="bg-green-50 py-12">
    <div class="max-w-4xl mx-auto px-6">
      <h3 class="font-bold text-2xl">Agenda & Alur Kegiatan</h3>
      <ol class="mt-6 space-y-4 text-gray-700">
        <li><strong>1 - 7 Nov 2025:</strong> Orientasi & perkenalan instruktur</li>
        <li><strong>8 - 21 Nov 2025:</strong> Modul inti (video + tugas mingguan)</li>
        <li><strong>22 - 28 Nov 2025:</strong> Proyek praktik & review instruktur</li>
        <li><strong>29 Nov 2025:</strong> Presentasi proyek & penutupan</li>
      </ol>
    </div>
  </section>  <!-- INSTRUCTORS -->  <section id="instruktur" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="font-bold text-2xl">Instruktur Praktisi</h3>
    <div class="mt-6 grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
      <!-- Card 1 -->
      <div class="bg-white rounded-lg p-4 shadow flex flex-col items-center text-center">
        <img src="https://via.placeholder.com/120.png?text=Guru" alt="Instruktur" class="w-24 h-24 rounded-full object-cover">
        <h4 class="mt-3 font-semibold">Budi Santoso</h4>
        <p class="text-sm text-gray-600">Praktisi hortikultura & urban farming</p>
      </div>
      <!-- Card 2 -->
      <div class="bg-white rounded-lg p-4 shadow flex flex-col items-center text-center">
        <img src="https://via.placeholder.com/120.png?text=Guru" alt="Instruktur" class="w-24 h-24 rounded-full object-cover">
        <h4 class="mt-3 font-semibold">Siti Maharani</h4>
        <p class="text-sm text-gray-600">Ahli budidaya perikanan</p>
      </div>
      <!-- Card 3 -->
      <div class="bg-white rounded-lg p-4 shadow flex flex-col items-center text-center">
        <img src="https://via.placeholder.com/120.png?text=Guru" alt="Instruktur" class="w-24 h-24 rounded-full object-cover">
        <h4 class="mt-3 font-semibold">Andi Wirawan</h4>
        <p class="text-sm text-gray-600">Konsultan peternakan skala kecil</p>
      </div>
      <!-- Card 4 -->
      <div class="bg-white rounded-lg p-4 shadow flex flex-col items-center text-center">
        <img src="https://via.placeholder.com/120.png?text=Guru" alt="Instruktur" class="w-24 h-24 rounded-full object-cover">
        <h4 class="mt-3 font-semibold">Dewi Rahma</h4>
        <p class="text-sm text-gray-600">Spesialis smart farming & IoT</p>
      </div>
    </div>
  </section>  <!-- PRICING -->  <section id="pricing" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="font-bold text-2xl">Paket & Harga</h3>
    <div class="mt-6 grid md:grid-cols-3 gap-6">
      <div class="bg-white rounded-xl p-6 shadow">
        <h4 class="font-semibold text-lg">Paket Basic</h4>
        <p class="text-3xl font-bold mt-3">Rp99.000</p>
        <p class="mt-2 text-sm text-gray-600">Akses modul dasar & e-book</p>
        <a href="#daftar" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded">Daftar</a>
      </div>
      <div class="bg-white border-2 border-green-600 rounded-xl p-6 shadow-lg">
        <h4 class="font-semibold text-lg">Paket Pro <span class="text-sm text-gray-500">(Best value)</span></h4>
        <p class="text-3xl font-bold mt-3">Rp249.000</p>
        <p class="mt-2 text-sm text-gray-600">Akses semua kelas + sesi live</p>
        <a href="#daftar" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded">Daftar</a>
      </div>
      <div class="bg-white rounded-xl p-6 shadow">
        <h4 class="font-semibold text-lg">Paket Premium</h4>
        <p class="text-3xl font-bold mt-3">Rp499.000</p>
        <p class="mt-2 text-sm text-gray-600">Termasuk magang & konsultasi 1-on-1</p>
        <a href="#daftar" class="mt-4 inline-block bg-green-600 text-white px-4 py-2 rounded">Daftar</a>
      </div>
    </div>
  </section>  <!-- TESTIMONIALS -->  <section class="bg-white py-12">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h3 class="font-bold text-2xl">Cerita Peserta</h3>
      <div class="mt-6 grid md:grid-cols-3 gap-6">
        <div class="p-6 bg-green-50 rounded-lg shadow text-left">
          <p class="italic">"Kelasnya realistis, dari teori langsung dipraktikkan. Hasil panen meningkat!"</p>
          <p class="mt-3 font-semibold">— Rahmat, Petani</p>
        </div>
        <div class="p-6 bg-green-50 rounded-lg shadow text-left">
          <p class="italic">"Bimbingan instruktur sangat membantu. Sangat direkomendasikan."</p>
          <p class="mt-3 font-semibold">— Lina, Pemula</p>
        </div>
        <div class="p-6 bg-green-50 rounded-lg shadow text-left">
          <p class="italic">"Materinya modern, cocok untuk urban farming juga."</p>
          <p class="mt-3 font-semibold">— Fajar, Pengusaha Mikro</p>
        </div>
      </div>
    </div>
  </section>  <!-- FAQ -->  <section id="faq" class="max-w-4xl mx-auto px-6 py-12">
    <h3 class="font-bold text-2xl">Pertanyaan Umum</h3>
    <div class="mt-6 space-y-4">
      <details class="bg-white p-4 rounded-lg shadow"><summary class="font-semibold">Siapa saja yang bisa ikut?</summary><div class="mt-2 text-sm text-gray-700">Siapa pun—pemula, petani pemula, anak muda yang ingin belajar urban farming, hingga pelaku usaha kecil.</div></details>
      <details class="bg-white p-4 rounded-lg shadow"><summary class="font-semibold">Apakah ada sertifikat?</summary><div class="mt-2 text-sm text-gray-700">Ya, setiap peserta yang menyelesaikan tugas dan proyek mendapatkan sertifikat digital.</div></details>
      <details class="bg-white p-4 rounded-lg shadow"><summary class="font-semibold">Apakah ada magang?</summary><div class="mt-2 text-sm text-gray-700">Untuk paket Premium tersedia kesempatan magang di mitra kami.</div></details>
    </div>
  </section>  <!-- CTA / REGISTER FORM -->  <section id="daftar" class="bg-green-600 text-white py-12">
    <div class="max-w-4xl mx-auto px-6">
      <div class="grid md:grid-cols-2 gap-6 items-center">
        <div>
          <h3 class="text-2xl font-bold">Daftar Sekarang & Mulai Bertani</h3>
          <p class="mt-2 text-green-100">Isi data singkat — tim kami akan menghubungi untuk konfirmasi pembayaran dan akses kelas.</p>
        </div>
        <form class="bg-white p-6 rounded-lg shadow text-gray-800" action="#" method="POST">
          <div class="grid grid-cols-1 gap-3">
            <input name="nama" required placeholder="Nama Lengkap" class="p-3 border rounded" />
            <input name="email" type="email" required placeholder="Email" class="p-3 border rounded" />
            <input name="hp" placeholder="No. WhatsApp" class="p-3 border rounded" />
            <select name="paket" class="p-3 border rounded">
              <option value="basic">Paket Basic - Rp99.000</option>
              <option value="pro">Paket Pro - Rp249.000</option>
              <option value="premium">Paket Premium - Rp499.000</option>
            </select>
            <button type="submit" class="mt-2 bg-green-600 text-white px-4 py-3 rounded">Kirim Pendaftaran</button>
          </div>
        </form>
      </div>
    </div>
  </section>  <!-- FOOTER -->  <footer class="bg-gray-900 text-gray-200 py-8">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-3 gap-6">
      <div>
        <h4 class="font-bold">TaniPintar</h4>
        <p class="text-sm mt-2">Platform pendidikan pertanian modern. Hubungi kami untuk kerjasama mitra.</p>
      </div>
      <div>
        <h5 class="font-semibold">Kontak</h5>
        <p class="text-sm mt-2">email: info@tanipintar.id<br/>WA: +62 812-3456-7890</p>
      </div>
      <div>
        <h5 class="font-semibold">Ikuti Kami</h5>
        <div class="mt-2 flex gap-3">
          <a href="#">Instagram</a>
          <a href="#">YouTube</a>
          <a href="#">TikTok</a>
        </div>
      </div>
    </div>
    <div class="mt-6 text-center text-xs text-gray-500">© 2025 TaniPintar. Semua hak dilindungi.</div>
  </footer>  <script>
    // Simple form handler (local demo)
    document.querySelectorAll('form[action="#"]').forEach(f => {
      f.addEventListener('submit', e => {
        e.preventDefault();
        alert('Terima kasih! Pendaftaran Anda telah dikirim. Tim TaniPintar akan menghubungi Anda.');
        f.reset();
        window.location.hash = '#';
      });
    });
  </script></body>
</html>
