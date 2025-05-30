# Halo Guys,Aku Jualan Aneka Macam Bakso,Di beli Yaa 
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bakso Dar Der Dor - Tempatnya Bakso Enak!</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      background: 
        radial-gradient(circle at 20% 30%, #ff6f61 15%, transparent 60%),
        radial-gradient(circle at 80% 70%, #ffe066 15%, transparent 60%),
        linear-gradient(135deg, #ee9ca7 0%, #ffdde1 100%);
      color: #333;
    }
    header {
      background-color: #d63031;
      color: white;
      padding: 2rem;
      text-align: center;
      box-shadow: 0 4px 8px rgba(214, 44, 45, 0.6);
      position: relative;
      z-index: 2;
    }
    header h1 {
      margin: 0;
      font-weight: 700;
      font-size: 2.7rem;
      letter-spacing: 1px;
      text-shadow: 0 2px 6px rgba(0,0,0,0.3);
    }
    header p.subtitle {
      margin-top: 0.25rem;
      font-size: 1.1rem;
      font-style: italic;
      font-weight: 400;
      opacity: 0.85;
      text-shadow: 0 1px 3px rgba(0,0,0,0.2);
    }
    header p.description {
      margin-top: 0.5rem;
      font-size: 1.3rem;
      font-weight: 400;
      opacity: 0.9;
      text-shadow: 0 1px 4px rgba(0,0,0,0.25);
    }
    main {
      flex-grow: 1;
      padding: 3rem 1rem 4rem;
      max-width: 900px;
      margin: 0 auto;
      width: 100%;
      position: relative;
      z-index: 2;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2.5rem;
      background: #ffffffdd;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(214, 44, 45, 0.3);
      backdrop-filter: saturate(180%) blur(12px);
      -webkit-backdrop-filter: saturate(180%) blur(12px);
    }
    .product-card {
      background: #fff7f7;
      border-radius: 16px;
      padding: 1.8rem 1.5rem 2rem;
      box-shadow: 0 6px 18px rgba(214, 44, 45, 0.15);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: transform 0.35s cubic-bezier(0.22, 1, 0.36, 1), box-shadow 0.35s ease;
    }
    .product-card:hover {
      transform: translateY(-10px) scale(1.03);
      box-shadow: 0 15px 36px rgba(214, 44, 45, 0.4);
    }
    .product-title {
      font-size: 1.6rem;
      font-weight: 700;
      color: #d63031;
      margin-bottom: 0.6rem;
      letter-spacing: 0.03em;
      text-shadow: 1px 1px 3px rgba(255, 105, 97, 0.4);
    }
    .product-desc {
      font-size: 1rem;
      flex-grow: 1;
      margin-bottom: 1rem;
      color: #555;
      line-height: 1.4;
    }
    .note-cheese {
      font-size: 0.9rem;
      font-style: italic;
      color: #d63031;
      margin-top: -0.1rem;
      margin-bottom: 1.1rem;
      font-weight: 600;
      letter-spacing: 0.02em;
    }
    .product-price {
      font-weight: 800;
      font-size: 1.35rem;
      color: #2d3436;
      margin-bottom: 1.5rem;
      letter-spacing: 0.05em;
      text-shadow: 0 1px 1px rgba(0,0,0,0.1);
    }
    .btn-order {
      background-color: #d63031;
      color: white;
      border: none;
      padding: 0.85rem 1.3rem;
      font-size: 1.1rem;
      font-weight: 700;
      border-radius: 12px;
      cursor: pointer;
      text-align: center;
      text-decoration: none;
      user-select: none;
      transition: background-color 0.35s cubic-bezier(0.22, 1, 0.36, 1);
      display: inline-block;
      box-shadow: 0 5px 15px rgba(214, 44, 45, 0.4);
      letter-spacing: 0.05em;
    }
    .btn-order:hover {
      background-color: #e17055;
      box-shadow: 0 8px 24px rgba(225, 112, 85, 0.6);
    }
    footer {
      background-color: #d63031;
      color: white;
      text-align: center;
      padding: 1rem 0;
      font-size: 0.94rem;
      user-select: none;
      margin-top: auto;
      box-shadow: 0 -4px 8px rgba(214, 44, 45, 0.6);
    }
    @media (max-width: 480px) {
      header h1 {
        font-size: 2.2rem;
      }
      header p.description {
        font-size: 1.1rem;
      }
      main {
        padding: 2rem 1rem 3rem;
      }
      .product-title {
        font-size: 1.4rem;
      }
      .product-price {
        font-size: 1.2rem;
      }
      .btn-order {
        font-size: 1rem;
        padding: 0.65rem 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Bakso Dar Der Dor</h1>
    <p class="subtitle">dibuat oleh Faiturrahman</p>
    <p class="description">Bakso Keju, Bakso Urat Pedas & Paket Bakso Pangsit</p>
  </header>
  <main>
    <div class="products" role="list">
      <article class="product-card" role="listitem">
        <h2 class="product-title">Bakso Keju</h2>
        <p class="product-desc">Lezatnya bakso dengan kejunya yang meleleh di mulut. Cocok untuk pecinta rasa gurih dan creamy.</p>
        <p class="note-cheese">*Catatan: Keju yang digunakan adalah keju cheddar, bukan mozzarella.</p>
        <p class="product-price">Harga: 5.000 IDR</p>
        <a href="https://wa.me/628871850109?text=Saya%20mau%20pesan%20Bakso%20Keju" class="btn-order" target="_blank" rel="noopener">Pesan via WhatsApp</a>
      </article>
      <article class="product-card" role="listitem">
        <h2 class="product-title">Bakso Urat Pedas</h2>
        <p class="product-desc">Bakso urat dengan bumbu pedas menggigit, membuat sensasi makan jadi makin mantap dan nagih.</p>
        <p class="product-price">Harga: 5.000 IDR</p>
        <a href="https://wa.me/628871850109?text=Saya%20mau%20pesan%20Bakso%20Urat%20Pedas" class="btn-order" target="_blank" rel="noopener">Pesan via WhatsApp</a>
      </article>
      <article class="product-card" role="listitem">
        <h2 class="product-title">Paket Bakso Pangsit</h2>
        <p class="product-desc">Paket komplit nikmat, berisi bakso dan pangsit yang siap memanjakan lidah kamu dalam satu genggaman.</p>
        <p class="product-price">Harga: 15.000 IDR</p>
        <a href="https://wa.me/628871850109?text=Saya%20mau%20pesan%20Paket%20Bakso%20Pangsit" class="btn-order" target="_blank" rel="noopener">Pesan via WhatsApp</a>
      </article>
    </div>
  </main>
  <footer>
    &copy; 2024 Bakso Dar Der Dor - Hubungi kami di WhatsApp: 0887 185 0109
  </footer>
</body>
</html>
