[portfolio_index.html](https://github.com/user-attachments/files/22939585/portfolio_index.html)
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portofolio Saya</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(120deg, #89f7fe, #66a6ff);
      color: #333;
    }
    header {
      background-color: rgba(255,255,255,0.9);
      text-align: center;
      padding: 2rem 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #2d2d2d;
    }
    header p {
      margin: .5rem 0 0;
      font-size: 1.1rem;
      color: #555;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      background: #fff;
      border-radius: 12px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    h2 {
      color: #0077ff;
      border-left: 5px solid #0077ff;
      padding-left: .5rem;
    }
    .project {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1rem;
    }
    .project img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: rgba(255,255,255,0.8);
      font-size: .9rem;
    }
    @media (max-width: 700px) {
      .project {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Radit Irawan</h1>
    <p>Desainer Grafis & Editor Video</p>
  </header>
  <main>
    <section>
      <h2>Tentang Saya</h2>
      <p>Saya seorang mahasiswa DKV dengan minat besar dalam desain grafis, fotografi, dan videografi. Berpengalaman menggunakan software seperti Adobe Illustrator, Photoshop, Lightroom, dan CapCut untuk menciptakan karya visual yang menarik dan bermakna.</p>
    </section>
    <section>
      <h2>Keahlian</h2>
      <ul>
        <li>Fotografi & Color Grading</li>
        <li>Desain Poster & Logo</li>
        <li>Editing Video</li>
        <li>Adobe Illustrator, Photoshop, CapCut, Canva</li>
      </ul>
    </section>
    <section>
      <h2>Portofolio</h2>
      <div class="project">
        <div>
          <img src="https://files.catbox.moe/io6v1b.png" alt="Karya 1">
        </div>
        <div>
          <img src="https://files.catbox.moe/wcphd4.mp3" alt="Karya 2">
        </div>
      </div>
    </section>
    <section>
      <h2>Kontak</h2>
      <p>Email: <a href="mailto:raditirawan@email.com">raditirawan@email.com</a></p>
      <p>Instagram: <a href="https://instagram.com/username" target="_blank">@username</a></p>
      <p>GitHub: <a href="https://github.com/username" target="_blank">github.com/username</a></p>
    </section>
  </main>
  <footer>
    <p>© 2025 Radit Irawan. Semua Hak Dilindungi.</p>
  </footer>
</body>
</html>
