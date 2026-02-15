<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <title>متجري الإلكتروني</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
      min-height: 100vh;
    }

    header {
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0,0,0,0.4);
      backdrop-filter: blur(10px);
    }

    header h1 {
      font-size: 28px;
      color: #00eaff;
    }

    nav a {
      margin-right: 20px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00eaff;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
    }

    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
      opacity: 0.9;
      margin-bottom: 40px;
    }

    .hero button {
      padding: 15px 35px;
      font-size: 18px;
      border: none;
      border-radius: 30px;
      background: #00eaff;
      color: #000;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .hero button:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,234,255,0.4);
    }

    .products {
      padding: 60px 40px;
    }

    .products h3 {
      text-align: center;
      font-size: 36px;
      margin-bottom: 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background: rgba(255,255,255,0.08);
      border-radius: 20px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card img {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 15px;
    }

    .card h4 {
      margin-bottom: 10px;
      font-size: 22px;
    }

    .card p {
      opacity: 0.85;
      margin-bottom: 15px;
    }

    .card span {
      font-size: 20px;
      color: #00eaff;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.4);
      margin-top: 60px;
    }
  </style>
</head>

<body>

<header>
  <h1>🛒 متجري</h1>
  <nav>
    <a href="#">الرئيسية</a>
    <a href="#">المنتجات</a>
    <a href="#">من نحن</a>
    <a href="#">تواصل معنا</a>
  </nav>
</header>

<section class="hero">
  <h2>تجربة تسوق فاخرة</h2>
  <p>أفضل المنتجات بأحدث التصاميم وبأسعار تنافسية</p>
  <button>تسوق الآن</button>
</section>

<section class="products">
  <h3>منتجات مميزة</h3>

  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="">
      <h4>منتج أنيق</h4>
      <p>وصف مختصر للمنتج</p>
      <span>$49</span>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="">
      <h4>منتج عصري</h4>
      <p>وصف مختصر للمنتج</p>
      <span>$79</span>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="">
      <h4>منتج فاخر</h4>
      <p>وصف مختصر للمنتج</p>
      <span>$99</span>
    </div>
  </div>
</section>

<footer>
  © 2026 جميع الحقوق محفوظة | متجري الإلكتروني
</footer>

</body>
</html>
