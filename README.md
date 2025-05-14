<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bakso Babeh – Baksonya Bikin Nagih!</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #fff;
      color: #333;
    }

    header {
      background-color: #c62828;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: #ffeb3b;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 600;
    }

    .hero {
      background: url('https://example.com/bakso-image.jpg') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 48px;
      font-weight: 600;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px #000;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 20px;
    }

    .hero .cta {
      background-color: #ffeb3b;
      color: #000;
      padding: 15px 30px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      text-transform: uppercase;
      cursor: pointer;
      margin: 5px;
    }

    .features {
      display: flex;
      justify-content: space-around;
      padding: 40px 20px;
      background-color: #fff7f7;
    }

    .features div {
      text-align: center;
      max-width: 200px;
    }

    .features div h3 {
      margin-top: 10px;
      font-size: 18px;
    }

    .promo {
      background-color: #ffc107;
      text-align: center;
      padding: 20px;
      font-size: 18px;
      font-weight: bold;
    }

    footer {
      background-color: #c62828;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 768px) {
      .features {
        flex-direction: column;
        align-items: center;
      }

      .hero h1 {
        font-size: 32px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">🍜 <strong>Bakso Babeh</strong></div>
  <nav>
    <a href="#">Beranda</a>
    <a href="#">Tentang</a>
    <a href="#">Produk</a>
    <a href="#">Promo</a>
    <a href="#">Lokasi</a>
    <a href="#">Kontak</a>
  </nav>
</header>

<section class="hero">
  <h1>Bakso Babeh</h1>
  <p>Baksonya Bikin Nagih!</p>
  <button class="cta">Pesan Sekarang</button>
  <button class="cta">Lihat Produk</button>
</section>

<section class="features">
  <div>
    <img src="https://img.icons8.com/ios-filled/50/000000/beef.png" alt="Daging Asli"/>
    <h3>Daging Sapi Asli</h3>
  </div>
  <div>
    <img src="https://img.icons8.com/ios-filled/50/000000/no-preservatives.png" alt="Tanpa Pengawet"/>
    <h3>Tanpa Pengawet</h3>
  </div>
  <div>
    <img src="https://img.icons8.com/ios-filled/50/000000/star.png" alt="Rasa Juara"/>
    <h3>Rasa Juara</h3>
  </div>
</section>

<section class="promo">
  🎉 Diskon 10% khusus pembelian di Naga Swalayan!
</section>

<footer>
  <p>&copy; 2025 Bakso Babeh. Ikuti kami di <a href="https://instagram.com/babehbakso_official" style="color:#ffeb3b;">@babehbakso_official</a></p>
</footer>

</body>
</html>

