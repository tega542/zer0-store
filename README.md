<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Zer0 - متجر ملابس رجالي</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo&display=swap');
    body {
      margin: 0; padding: 0;
      font-family: 'Cairo', sans-serif;
      background-color: #000;
      color: #eee;
      direction: rtl;
    }
    header {
      background: #111;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #0ff;
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
      color: #0ff;
    }
    nav {
      margin: 15px auto;
      text-align: center;
    }
    nav button {
      background: #0ff;
      border: none;
      color: #000;
      padding: 10px 20px;
      margin: 0 10px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }
    nav button:hover {
      background: #0cc;
    }
    main {
      max-width: 1000px;
      margin: 30px auto;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }
    .product {
      background: #111;
      border: 1px solid #0ff;
      border-radius: 10px;
      width: 280px;
      padding: 15px;
      box-sizing: border-box;
      transition: box-shadow 0.3s;
    }
    .product:hover {
      box-shadow: 0 0 15px #0ff;
    }
    .product img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }
    .product h3 {
      margin: 0 0 10px;
      font-size: 20px;
      color: #0ff;
    }
    .product p {
      margin: 0 0 15px;
      color: #ccc;
      font-size: 14px;
      min-height: 40px;
    }
    .product .price {
      font-size: 18px;
      font-weight: bold;
      color: #0ff;
      margin-bottom: 15px;
    }
    .product button {
      background: #0ff;
      border: none;
      color: #000;
      padding: 10px;
      width: 100%;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .product button:hover {
      background: #0cc;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #0ff;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    Zer0 - متجر الملابس الرجالي
  </header>
  <nav>
    <button onclick="alert('ميزة تسجيل الدخول سيتم تطويرها قريبًا')">تسجيل دخول</button>
    <button onclick="alert('ميزة الدفع سيتم تطويرها قريبًا')">الدفع أونلاين</button>
  </nav>
  <main>
    <div class="product">
      <img src="https://i.imgur.com/J4q0nGf.jpg" alt="قميص كاجوال" />
      <h3>قميص كاجوال</h3>
      <p>قميص ناعم مريح للبس اليومي بلون أبيض.</p>
      <div class="price">350 جنيه</div>
      <button>أضف للسلة</button>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/ZQLxG7K.jpg" alt="تيشيرت سبورت" />
      <h3>تيشيرت سبورت</h3>
      <p>تيشيرت بقطن عالي الجودة للتمرين والراحة.</p>
      <div class="price">420 جنيه</div>
      <button>أضف للسلة</button>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/HFqCWbb.jpg" alt="جاكيت كلاسيك" />
      <h3>جاكيت كلاسيك</h3>
      <p>جاكيت أنيق بأسلوب كلاسيكي يناسب كل المناسبات.</p>
      <div class="price">750 جنيه</div>
      <button>أضف للسلة</button>
    </div>
  </main>
  <footer>
    &copy; 2025 Zer0. كل الحقوق محفوظة.
  </footer>
</body>
</html>
