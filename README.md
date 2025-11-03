<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NOKA Group - Digital Agriculture Ecosystem</title>
<script src="https://cdn.tailwindcss.com"></script>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
  /* Fade-up animation */
  .fade-up { opacity: 0; transform: translateY(40px); transition: all 0.8s ease-out; }
  .fade-up.visible { opacity: 1; transform: translateY(0); }

  /* Smooth scroll */
  html { scroll-behavior: smooth; }

  /* Parallax hero */
  .parallax { background-attachment: fixed; background-size: cover; background-position: center; }

  /* Modal */
  .modal { display: none; position: fixed; z-index: 1000; left: 0; top: 0; width: 100%; height: 100%; overflow:auto; background-color: rgba(0,0,0,0.7); }
  .modal-content { background-color: #fff; margin: 10% auto; padding: 1rem; border-radius: 0.5rem; max-width: 800px; position: relative; }
  .close { position: absolute; top: 10px; right: 15px; font-size: 1.5rem; cursor: pointer; }

  /* Horizontal roadmap scroll */
  .roadmap-container { display: flex; overflow-x:auto; gap:2rem; padding-bottom:1rem; }
  .roadmap-container::-webkit-scrollbar { height:8px; }
  .roadmap-container::-webkit-scrollbar-thumb { background:#16A34A; border-radius:4px; }
</style>
</head>
<body class="bg-gray-50 font-sans">

<!-- Hero Section -->
<section class="relative h-screen parallax">
  <video autoplay muted loop class="absolute w-full h-full object-cover">
    <source src="https://github.com/sobatnoka/sobatnoka.github.io/raw/main/hero_video.mp4" type="video/mp4">
  </video>
  <div class="absolute inset-0 bg-green-900 bg-opacity-50 flex flex-col justify-center items-center text-center px-6">
    <h1 class="text-4xl md:text-5xl font-bold text-white mb-4 opacity-0 transform translate-y-8 fade-up">Transforming Indonesian Agriculture</h1>
    <p class="text-lg md:text-xl text-white mb-8 opacity-0 transform translate-y-8 fade-up">End-to-End Digital Ecosystem: Education, Community, Marketplace, Fintech & Sustainability</p>
    <a href="#contact" class="bg-white text-green-700 font-semibold py-3 px-6 rounded shadow hover:bg-gray-100 transition opacity-0 transform translate-y-8 fade-up">Invest Now</a>
    <div class="mt-10 animate-bounce text-white">↓ Scroll</div>
  </div>
</section>

<!-- About Section -->
<section id="about" class="py-20">
  <div class="container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-6 text-green-700 fade-up">About NOKA Group</h2>
    <p class="text-gray-700 max-w-3xl mx-auto mb-6 fade-up">
      NOKA Group is an integrated digital agriculture ecosystem that empowers farmers, improves supply chain efficiency, and drives agricultural economic growth through technology, fintech, and digital innovation.
    </p>
    <p class="text-gray-700 max-w-3xl mx-auto fade-up">
      It consists of 7 main divisions: <strong>TaniPintar, TaniLink, TaniPay, TaniCoin, TaniBank, TaniMall, and TaniPeduli</strong>, supporting education, community, marketplace, digital payments, financing, tokenization, and sustainable agriculture.
    </p>
  </div>
</section>

<!-- Ecosystem Section -->
<section id="ecosystem" class="bg-gray-100 py-20">
  <div class="container mx-auto px-6">
    <h2 class="text-3xl font-bold mb-12 text-center text-green-700 fade-up">Our Ecosystem</h2>
    <div class="grid md:grid-cols-3 gap-8 text-center">
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniPintar</h3>
        <p>Digital education & certification for farmers through online classes, webinars & e-books.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniLink</h3>
        <p>Farmer community & mentorship, workshops, networking, and support system.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniMall</h3>
        <p>Agricultural B2C & B2B marketplace, logistics, premium stores, and digital export.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniPay</h3>
        <p>Fintech & digital wallet, payments, top-up, remittance, ecosystem integration.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniBank</h3>
        <p>Agribusiness financing & DeFi, productive loans, invoice financing, yield DeFi.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniCoin</h3>
        <p>Token & reward system, staking, NFTs, and ecosystem transaction driver.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition fade-up">
        <h3 class="text-xl font-semibold mb-2 text-green-700">TaniPeduli</h3>
        <p>ESG program, green farming, donations, and carbon credits.</p>
      </div>
    </div>
  </div>
</section>

<!-- Roadmap Section -->
<section id="roadmap" class="py-20">
  <div class="container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-12 text-green-700 fade-up">Roadmap 2025-2035</h2>
    <div class="roadmap-container fade-up">
      <div class="bg-white p-6 rounded shadow min-w-[250px]">
        <h3 class="font-semibold text-green-700 mb-2">2025-2026</h3>
        <p>MVP, community validation & platform launch</p>
      </div>
      <div class="bg-white p-6 rounded shadow min-w-[250px]">
        <h3 class="font-semibold text-green-700 mb-2">2027-2028</h3>
        <p>National scalability, mobile apps, Marketplace 2.0</p>
      </div>
      <div class="bg-white p-6 rounded shadow min-w-[250px]">
        <h3 class="font-semibold text-green-700 mb-2">2029-2030</h3>
        <p>Blockchain, smart supply chain, fintech integration</p>
      </div>
      <div class="bg-white p-6 rounded shadow min-w-[250px]">
        <h3 class="font-semibold text-green-700 mb-2">2031-2032</h3>
        <p>ASEAN expansion, global partnerships, AI & IoT</p>
      </div>
      <div class="bg-white p-6 rounded shadow min-w-[250px]">
        <h3 class="font-semibold text-green-700 mb-2">2033-2035</h3>
        <p>Global platform, DAO, AgriNFT, IPO</p>
      </div>
    </div>
  </div>
</section>

<!-- Financial Section -->
<section id="financials" class="bg-gray-100 py-20">
  <div class="container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-12 text-green-700 fade-up">Financial Projections</h2>
    <canvas id="revenueChart" class="max-w-4xl mx-auto fade-up"></canvas>
    <p class="text-gray-700 mt-6 max-w-2xl mx-auto fade-up">
      Pre-IPO valuation per division: TaniMall (Rp70T), TaniBank (Rp45T), TaniPay (Rp30T), TaniCoin (Rp25T), TaniPintar, TaniLink, TaniPeduli each Rp10T.
    </p>
  </div>
</section>

<!-- Investor Section -->
<section id="contact" class="bg-green-700 text-white py-20">
  <div class="container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-6 fade-up">InvestorRelations</h2>
    <p class="mb-6 fade-up">For partnership, investment, or inquiries, contact us or download the pitch deck:</p>
    <button id="openModal" class="bg-white text-green-700 font-semibold py-3 px-6 rounded shadow hover:bg-gray-100 transition mb-6 inline-block fade-up">Download / Preview Pitch Deck</button>

    <!-- Investor Form -->
    <form class="max-w-xl mx-auto mt-6 space-y-4 bg-white p-6 rounded shadow text-gray-700 fade-up">
      <input type="text" placeholder="Full Name" class="w-full border border-gray-300 p-3 rounded" required>
      <input type="email" placeholder="Email Address" class="w-full border border-gray-300 p-3 rounded" required>
      <textarea placeholder="Message / Inquiry" class="w-full border border-gray-300 p-3 rounded" rows="4" required></textarea>
      <button type="submit" class="bg-green-700 text-white font-semibold py-3 px-6 rounded shadow hover:bg-green-800 transition w-full">Submit</button>
    </form>
  </div>
</section>

<!-- Modal -->
<div id="pitchModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h3 class="font-bold text-green-700 text-xl mb-4">NOKA Group Investor Pitch Deck</h3>
    <iframe src="NOKA_Investor_PitchDeck.pdf" class="w-full h-96" frameborder="0"></iframe>
    <a href="NOKA_Investor_PitchDeck.pdf" download class="mt-4 inline-block bg-green-700 text-white font-semibold py-2 px-4 rounded hover:bg-green-800 transition">Download PDF</a>
  </div>
</div>

<!-- Footer -->
<footer class="bg-white shadow py-6 text-center text-gray-600">
  &copy; 2025 NOKA Group. All rights reserved.
</footer>

<!-- Scripts -->
<script>
  // Fade-up animation on scroll
  const faders = document.querySelectorAll('.fade-up');
  const appearOptions = { threshold: 0.2, rootMargin: "0px 0px -50px 0px" };
  const appearOnScroll = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => { 
      if(entry.isIntersecting){ 
        entry.target.classList.add('visible'); 
        observer.unobserve(entry.target); 
      } 
    });
  }, appearOptions);
  faders.forEach(fader => appearOnScroll.observe(fader));

  // Chart.js financial chart
  const ctx = document.getElementById('revenueChart').getContext('2d');
  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['TaniMall','TaniBank','TaniPay','TaniCoin','TaniPintar','TaniLink','TaniPeduli'],
      datasets: [{
        label: 'Pre-IPO Valuation (Rp Trillion)',
        data: [70,45,30,25,10,10,10],
        backgroundColor: ['#16A34A','#22C55E','#4ADE80','#A7F3D0','#6EE7B7','#34D399','#10B981'],
      }]
    },
    options: {
      responsive:true,
      plugins:{legend:{display:false},title:{display:true,text:'NOKA Group Valuation per Division',font:{size:18}}},
      scales:{y:{beginAtZero:true,title:{display:true,text:'Valuation (Rp Trillion)'}}}
    }
  });

  // Modal functionality
  const modal = document.getElementById("pitchModal");
  const btn = document.getElementById("openModal");
  const span = document.getElementsByClassName("close")[0];
  btn.onclick = () => { modal.style.display = "block"; }
  span.onclick = () => { modal.style.display = "none"; }
  window.onclick = e => { if(e.target==modal){ modal.style.display = "none"; } }
</script>
</body>
</html>
