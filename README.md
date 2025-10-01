# Tugas-PBW
Tugas mata kuliah PBW Website Pribadi
<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Website Sederhana</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #333;
    }
    header, nav, main, aside, footer {
      padding: 15px;
      margin: 10px;
      border-radius: 8px;
    }
    header {
      background: #0b3d91;
      color: white;
    }
    nav {
      background: #ffb703;
    }
    nav a {
      margin-right: 10px;
      text-decoration: none;
      color: #000;
      font-weight: bold;
    }
    main {
      display: flex;
      gap: 10px;
    }
    article {
      flex: 3;
      position: relative;
      background: none;
      padding: 15px;
      border-radius: 8px;
      margin-left: -10px;
    }
    article::before {
      content: "";
      position: absolute;
      inset: 0;
      background-image: url('freepik__the-style-is-candid-image-photography-with-natural__51927.jpeg');
      background-size: cover;
      background-position: center;
      opacity: 0.2;
      z-index: 0;
      border-radius: 8px;
    }
    article > * {
      position: relative;
      z-index: 1;
    }
    aside {
      flex: 1;
      background: white;
      padding: 15px;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      background: #ddd;
      font-size: 0.9em;
    }
    .highlight {
      background: yellow;
      padding: 2px 5px;
      border-radius: 4px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Website Sederhana</h1>
    <p></p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <article>
      <h2 style="text-indent: 1em;">Konnichiwa</h2>
      <p style="text-indent: 2em;">Perkenalkan, nama saya Azmi Irsyad, mahasiswa dari Fakultas Ilmu Komputer jurusan Teknik Informatika di Universitas Dian Nuswantoro. Saya berasal dari Semarang dan saat ini sedang menempuh studi di semester 3. Selama menjalani perkuliahan, saya belajar banyak hal terkait dunia teknologi, mulai dari dasar-dasar pemrograman hingga penerapan logika komputasi dalam berbagai bidang.</p>
      <p style="text-indent: 2em;">Saya memiliki minat yang besar terhadap dunia teknologi, khususnya dalam bidang pemrograman dan pengembangan sistem. Bagi saya, menjadi mahasiswa informatika bukan hanya tentang memahami kode, tetapi juga tentang menciptakan solusi yang bermanfaat bagi banyak orang. Dengan semangat belajar dan keinginan untuk terus berkembang, saya berharap dapat menjadi pribadi yang berkompeten dan siap menghadapi tantangan di dunia teknologi.</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2025 — Contoh Website Pribadi</p>
  </footer>

</body>
</html>
