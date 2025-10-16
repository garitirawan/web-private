<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <title>Untitled</title>
    

  </head>
    
  <body>
  <!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio Saya - Radit Irawan</title>
  <style>
    /* ===== STYLE DASAR ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background-color: #0e0e0e;
      color: white;
    }

    header {
      background: #1a1a1a;
      padding: 20px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    header h1 {
      font-size: 24px;
      color: #ff4b2b;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
    }

    nav a:hover {
      color: #ff4b2b;
    }

    /* ===== HERO SECTION ===== */
    .hero {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80') center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    .hero h2 {
      font-size: 48px;
      margin-bottom: 10px;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.6);
    }

    .hero p {
      font-size: 20px;
      max-width: 600px;
    }

    .btn {
      margin-top: 20px;
      background: #ff4b2b;
      padding: 12px 30px;
      border: none;
      border-radius: 8px;
      color: white;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ff6f61;
    }

    /* ===== ABOUT ===== */
    section {
      padding: 80px 100px;
    }

    .about {
      display: flex;
      align-items: center;
      gap: 50px;
    }

    .about img {
      width: 300px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(255,75,43,0.3);
    }

    .about-text h3 {
      color: #ff4b2b;
      font-size: 30px;
      margin-bottom: 10px;
    }

    .about-text p {
      line-height: 1.6;
    }

    /* ===== SKILLS ===== */
    .skills {
      background: #1a1a1a;
      border-radius: 15px;
      padding: 50px;
    }

    .skills h3 {
      color: #ff4b2b;
      margin-bottom: 20px;
    }

    .skill-bar {
      margin: 15px 0;
    }

    .skill-bar p {
      margin-bottom: 5px;
    }

    .bar {
      background: #333;
      border-radius: 10px;
      overflow: hidden;
    }

    .bar-fill {
      background: #ff4b2b;
      height: 12px;
      width: 0;
      border-radius: 10px;
      transition: width 1s;
    }

    /* ===== PORTFOLIO ===== */
    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .project {
      background: #1a1a1a;
      border-radius: 15px;
      overflow: hidden;
      transition: transform 0.3s;
    }

    .project:hover {
      transform: scale(1.05);
    }

    .project img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .project h4 {
      padding: 15px;
    }

    /* ===== FOOTER ===== */
    footer {
      text-align: center;
      padding: 30px;
      background: #111;
      color: #aaa;
    }

    footer a {
      color: #ff4b2b;
      text-decoration: none;
    }

    @media(max-width:768px) {
      .about {
        flex-direction: column;
        text-align: center;
      }
      section {
        padding: 60px 30px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Radit Irawan</h1>
    <nav>
      <a href="#about">Tentang</a>
      <a href="#skills">Skill</a>
      <a href="#portfolio">Proyek</a>
      <a href="#contact">Kontak</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Halo, Saya Radit Irawan👋</h2>
    <p>Seorang Desainer Komunikasi Visual dengan passion di bidang fotografi, video editing, dan desain grafis.</p>
    <button class="btn" onclick="document.getElementById('portfolio').scrollIntoView()">Lihat Portofolio</button>
  </section>

  <section id="about" class="about">
    <img src="https://files.catbox.moe/io6v1b.png" alt="Foto Profil">
    <div class="about-text">
      <h3>Tentang Saya</h3>
      <p>
        Saya adalah lulusan dari SMK jurusan DKV yang suka menciptakan karya visual yang menarik dan bermakna.
        Skill saya meliputi fotografi, editing video, color grading, desain poster, dan pembuatan logo.
        Saya menggunakan software seperti Adobe Photoshop, Illustrator, CapCut, Canva, dan Lightroom.
      </p>
    </div>
  </section>

  <section id="skills" class="skills">
    <h3>Skill Saya</h3>
    <div class="skill-bar">
      <p>Adobe Photoshop</p>
      <div class="bar"><div class="bar-fill" style="width:80%"></div></div>
    </div>
    <div class="skill-bar">
      <p>Adobe Illustrator</p>
      <div class="bar"><div class="bar-fill" style="width:80%"></div></div>
    </div>
    <div class="skill-bar">
      <p>Photography & Color Grading</p>
      <div class="bar"><div class="bar-fill" style="width:90%"></div></div>
    </div>
    <div class="skill-bar">
      <p>Video Editing (CapCut, Premiere)</p>
      <div class="bar"><div class="bar-fill" style="width:75%"></div></div>
    </div>
  </section>

  <section id="portfolio">
    <h3 style="color:#ff4b2b; text-align:center; margin-bottom:30px;">Proyek Terbaru</h3>
    <div class="portfolio-grid">
      <div class="project">
        <img src="https://images.unsplash.com/photo-1611078489935-0cb964de46f0?auto=format&fit=crop&w=800&q=80" alt="">
        <h4>Desain Poster Kampanye Sosial</h4>
      </div>
      <div class="project">
        <img src="https://images.unsplash.com/photo-1621570079211-9a5d474fdd64?auto=format&fit=crop&w=800&q=80" alt="">
        <h4>Logo Brand Lokal</h4>
      </div>
      <div class="project">
        <img src="https://images.unsplash.com/photo-1518972559570-7cc1309f3229?auto=format&fit=crop&w=800&q=80" alt="">
        <h4>Fotografi Produk</h4>
      </div>
    </div>
  </section>

  <section id="contact" style="text-align:center;">
    <h3 style="color:#ff4b2b;">Hubungi Saya</h3>
    <p>Kamu bisa menghubungi saya lewat:</p>
    <p>Email: <a href="mailto:radit@example.com">radit@example.com</a></p>
    <p>Instagram: <a href="https://instagram.com" target="_blank">@radit.irawan</a></p>
  </section>

  <footer>
    <p>© 2025 Radit Irawan. Dibuat dengan ❤️ dan kreativitas.</p>
  </footer>

  <script>
    // Efek animasi bar skill saat di-scroll
    window.addEventListener('scroll', () => {
      document.querySelectorAll('.bar-fill').forEach(bar => {
        const rect = bar.getBoundingClientRect();
        if (rect.top < window.innerHeight && rect.bottom >= 0) {
          bar.style.transition = 'width 1.5s ease-out';
        }
      });
    });
  </script>
</body>
</html>
    
  </body>
  
</html>
