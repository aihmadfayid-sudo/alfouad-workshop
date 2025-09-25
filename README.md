<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ورشة الفؤاد للمقاولات</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: \"Tajawal\", sans-serif;
      color: #333;
      background-color: #f9f9f9;
    }
    header {
      background: #ffffff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 0;
    }
    nav a {
      text-decoration: none;
      color: #333;
      margin: 0 10px;
      font-weight: bold;
    }
    nav a:hover {
      color: #007bff;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 80px 0;
    }
    .hero .text {
      max-width: 600px;
    }
    .hero h1 {
      font-size: 2.8rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #555;
    }
    .hero .btn {
      display: inline-block;
      padding: 12px 30px;
      background: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1rem;
    }
    .hero .btn:hover {
      background: #0056b3;
    }
    .hero .image {
      max-width: 45%;
    }
    .hero .image img {
      width: 100%;
      border-radius: 10px;
    }

    section {
      padding: 60px 0;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
    }
    section .subtext {
      text-align: center;
      color: #555;
      margin-bottom: 40px;
    }

    .services .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }
    .services .card {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      padding: 30px;
      text-align: center;
    }
    .services .card h3 {
      margin-bottom: 15px;
      font-size: 1.3rem;
    }
    .services .card p {
      color: #666;
      font-size: 1rem;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
      object-fit: cover;
      height: 200px;
    }

    .contact {
      max-width: 600px;
      margin: 0 auto;
    }
    .contact form {
      display: grid;
      gap: 20px;
    }
    .contact input,
    .contact textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    .contact button {
      padding: 14px 0;
      background: #007bff;
      color: #fff;
      border: none;
      border-radius: 6px;
      font-size: 1.1rem;
      cursor: pointer;
    }
    .contact button:hover {
      background: #0056b3;
    }

    footer {
      text-align: center;
      padding: 20px 0;
      background: #fff;
      color: #777;
      font-size: 0.9rem;
      border-top: 1px solid #eee;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <nav>
        <a href="#">ورشة الفؤاد</a>
        <div>
          <a href="#about">من نحن</a>
          <a href="#services">خدماتنا</a>
          <a href="#gallery">معرض الأعمال</a>
          <a href="#contact">تواصل معنا</a>
        </div>
      </nav>
    </div>
  </header>

  <section class="hero container">
    <div class="text">
      <h1>ورشة الفؤاد للمقاولات</h1>
      <p>متخصصون في المطابخ، الشبابيك، الأبواب والواجهات بألوميتال عالي الجودة.</p>
      <a class="btn" href="#contact">اطلب عرضًا الآن</a>
    </div>
    <div class="image">
      <img src="https://via.placeholder.com/500x400" alt="مشروع الفؤاد">
    </div>
  </section>

  <section id="about" class="container">
    <h2>من نحن</h2>
    <p class="subtext">نحن فريق محترف في مجال الألوميتال والمقاولات في دمنهور والبحيرة.</p>
    <p>نُقدّم خدمات متكاملة في تصميم، تنفيذ وتركيب المطابخ، الشبابيك، الأبواب، الواجهات والزجاج العصري. نحن نضمن الجودة، التسليم في الموعد، والدعم المتواصل.</p>
  </section>

  <section id="services" class="container services">
    <h2>خدماتنا</h2>
    <p class="subtext">ما نقدمه من خدمات متميزة لعملائنا</p>
    <div class="cards">
      <div class="card">
        <h3>مطابخ ألوميتال</h3>
        <p>تصميم مطابخ حسب الطلب وبأجود الخامات وبذوق عالي.</p>
      </div>
      <div class="card">
        <h3>شبابيك وأبواب</h3>
        <p>أنظمة متينة مع عزل صوتي وحراري وتصميم عصري.</p>
      </div>
      <div class="card">
        <h3>واجهات وزجاج</h3>
        <p>تنفيذ واجهات للمباني والمحلات بتصاميم حديثة.</p>
      </div>
    </div>
  </section>

  <section id="gallery" class="container">
    <h2>معرض الأعمال</h2>
    <p class="subtext">بعض من مشاريعنا المنفذة</p>
    <div class="gallery">
      <img src="https://via.placeholder.com/600x400" alt="مشروع 1">
      <img src="https://via.placeholder.com/600x400" alt="مشروع 2">
      <img src="https://via.placeholder.com/600x400" alt="مشروع 3">
    </div>
  </section>

  <section id="contact" class="container contact">
    <h2>تواصل معنا</h2>
    <p class="subtext">أرسل لنا رسالة وسنعاود الاتصال بك</p>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="الاسم" required />
      <input type="email" name="email" placeholder="البريد الإلكتروني" required />
      <textarea name="message" placeholder="رسالتك" rows="5" required></textarea>
      <button type="submit">أرسل</button>
    </form>
    <p style="text-align: center; margin-top: 15px;">📞 01004065882</p>
  </section>

  <footer>
    &copy; 2025 ورشة الفؤاد للمقاولات — جميع الحقوق محفوظة
  </footer>

  <script>
    // هنا يمكن إضافة بعض التفاعلات البسيطة مثل تمرير ناعم للرابطات
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth' });
        }
      });
    });
  </script>

</body>
</html>
