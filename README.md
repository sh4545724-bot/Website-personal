<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Nama Anda — Blog & Portofolio</title>
  <meta name="description" content="Blog pribadi — artikel, proyek, dan kontak." />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%23007ACC'/%3E%3Ctext x='50' y='57' font-size='48' text-anchor='middle' fill='white' font-family='Arial' font-weight='700'%3EM%3C/text%3E%3C/svg%3E" />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#9aa4b2;--accent:#07c}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;background:linear-gradient(180deg,#071022 0%,#07142a 100%);color:#e6eef6;line-height:1.5}
    .container{max-width:1024px;margin:0 auto;padding:28px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;background:var(--accent);border-radius:10px;display:flex;align-items:center;justify-content:center;font-weight:700}
    nav a{color:var(--muted);text-decoration:none;margin-left:14px;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr;gap:20px;margin:34px 0}
    .hero-card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:28px;border-radius:14px;box-shadow:0 6px 20px rgba(2,6,23,0.6)}
    h1{font-size:28px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0}
    .cta{display:inline-block;margin-top:14px;padding:10px 16px;border-radius:10px;background:var(--accent);color:#042; font-weight:700;text-decoration:none}
    .grid-2{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin-top:18px}
    .post{background:var(--card);padding:16px;border-radius:12px}
    .post h3{margin:0 0 8px}
    footer{margin-top:36px;color:var(--muted);font-size:14px;text-align:center}
    @media(min-width:800px){.hero{grid-template-columns:1.1fr .9fr}.hero h1{font-size:36px}}
    @media(max-width:799px){.grid-2{grid-template-columns:1fr}.container{padding:18px}}
    .tag{display:inline-block;padding:6px 8px;border-radius:999px;background:rgba(7,140,255,0.12);color:var(--accent);font-weight:700;font-size:13px}
    .muted{color:var(--muted)}
    form label{display:block;margin-top:10px;color:var(--muted);font-size:14px}
    input[type=text],input[type=email],textarea{width:100%;padding:10px;margin-top:6px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
    button{margin-top:10px;padding:10px 14px;border-radius:10px;border:0;background:var(--accent);color:#042;font-weight:700}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">M</div>
        <div>
          <div style="font-weight:800">Mass Corp</div>
          <div class="muted" style="font-size:13px">Blog & Portofolio</div>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#home">Home</a>
        <a href="#blog">Blog</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main class="hero">
      <section class="hero-card" id="home">
        <span class="tag">Artikel Baru</span>
        <h1>Halo — Saya Mass Corp. Menulis tentang teknologi, desain, dan produktivitas.</h1>
        <p class="lead">Template website sederhana, cepat, dan mudah diubah. Cocok untuk blog pribadi, portofolio, atau landing page.</p>
        <a class="cta" href="#blog">Baca Artikel</a>

        <div class="grid-2" style="margin-top:18px">
          <article class="post">
            <h3>Judul Postingan Contoh</h3>
            <p class="muted">Ringkasan singkat postingan. Tanggal • 3 menit baca</p>
          </article>
          <article class="post">
            <h3>Proyek Terbaru</h3>
            <p class="muted">Deskripsi proyek singkat dan link ke demo / repo.</p>
          </article>
        </div>
      </section>

      <aside class="hero-card" id="about">
        <h2>Tentang Saya</h2>
        <p class="muted">Saya penulis dan pembuat konten. Saya suka membangun hal-hal sederhana yang berguna untuk orang lain.</p>
        <h3 style="margin-top:16px">Layanan</h3>
        <ul class="muted">
          <li>Penulisan & konten</li>
          <li>Desain UI dasar</li>
          <li>Setup blog & SEO</li>
        </ul>
        <h3 style="margin-top:12px">Media Sosial</h3>
        <p class="muted">@masscorp — Twitter / Instagram / Tiktok</p>
      </aside>
    </main>

    <section style="margin-top:20px" id="blog">
      <h2>Artikel Terbaru</h2>
      <div class="grid-2" style="margin-top:12px">
        <article class="post">
          <h3>Cara Membuat Blog (Panduan Lengkap)</h3>
          <p class="muted">Langkah-langkah mudah untuk memulai blog — domain, hosting, dan tips SEO.</p>
        </article>
        <article class="post">
          <h3>Thumbnail YouTube yang Menarik</h3>
          <p class="muted">Tips cepat membuat thumbnail yang klik-bait tapi rapi.</p>
        </article>
      </div>
    </section>

    <section style="margin-top:24px" id="contact" class="hero-card">
      <h2>Kontak</h2>
      <p class="muted">Isi form berikut atau hubungi via email: <strong>hello@example.com</strong></p>
      <form onsubmit="handleForm(event)">
        <label for="name">Nama</label>
        <input id="name" name="name" type="text" placeholder="Nama Anda" required />
        <label for="email">Email</label>
        <input id="email" name="email" type="email" placeholder="email@contoh.com" required />
        <label for="message">Pesan</label>
        <textarea id="message" name="message" rows="4" placeholder="Tulis pesan..." required></textarea>
        <button type="submit">Kirim Pesan</button>
      </form>
    </section>

    <footer>
      <p>&copy; <span id="year"></span> Mass Corp — Dibuat dengan Template Single-File.</p>
    </footer>
  </div>

  <script>
    function handleForm(e){
      e.preventDefault();
      const name=document.getElementById('name').value.trim();
      alert('Terima kasih, '+(name||'pengunjung')+" — pesan Anda terkirim (demo).\nUntuk aktifkan form, hubungkan ke email atau server.");
      e.target.reset();
    }
    document.getElementById('year').textContent=new Date().getFullYear();
  </script>
</body>
</html>
