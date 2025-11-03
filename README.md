# فروشگاه اینترنتی صدرایی
نفیس" یک وب‌سایت خدمات زیبایی و مراقبت‌های سلامت است که با هدف معرفی درمان‌های باکیفیت، محصولات تخصصی و تجربه‌های آرامش‌بخش در زمینه زیبایی و تندرستی طراحی شده است.
این وب‌سایت فضایی مدرن و کاربرپسند فراهم می‌کند تا بازدیدکنندگان بتوانند با خدمات زیبایی، مراقبت از پوست و مو، مشاوره‌های تخصصی، و محصولات مراقبتی نفیس آشنا شوند و اطلاعات لازم را برای انتخاب بهترین گزینه متناسب با نیاز خود به‌دست آورند.
هدف ما در "نفیس" ایجاد پلی میان علم زیبایی و آرامش درونی است؛ جایی که هر فرد احساس خاص بودن و اعتماد‌به‌نفس بیشتری داشته باشد.<!doctype html>
<html lang="fa">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>فروشگاه من</title>
  <style>
    :root{--bg:#f7f7f9;--card:#fff;--accent:#0b74de}
    html,body{height:100%;margin:0;font-family: "Helvetica Neue", Arial, sans-serif;background:var(--bg);color:#222}
    .wrap{max-width:1100px;margin:30px auto;padding:16px}
    header{display:flex;align-items:center;justify-content:space-between;gap:12px}
    header h1{margin:0;font-size:1.6rem}
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:16px;margin-top:18px}
    .card{background:var(--card);border-radius:10px;box-shadow:0 2px 8px rgba(0,0,0,0.06);overflow:hidden;display:flex;flex-direction:column}
    .card img{width:100%;height:170px;object-fit:cover;background:#e9e9e9}
    .card .body{padding:12px;flex:1;display:flex;flex-direction:column}
    .title{font-weight:600;margin:0 0 8px 0}
    .price{margin-top:auto;font-weight:700}
    .buttons{display:flex;gap:8px;margin-top:10px}
    .btn{flex:1;padding:8px 10px;border-radius:8px;border:0;cursor:pointer;font-weight:600}
    .btn.contact{background:#eee}
    .btn.buy{background:var(--accent);color:#fff}
    footer{margin-top:24px;text-align:center;color:#666;font-size:0.9rem}
    @media (max-width:480px){ .card img{height:140px} header{flex-direction:column;align-items:flex-start} }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>فروشگاه محصولات من</h1>
      <nav>
        <a href="#products">محصولات</a>
        &nbsp;•&nbsp;
        <a href="#contact">تماس</a>
      </nav>
    </header>

    <section id="products" class="grid">
      <!-- محصول ۱ -->
      <article class="card">
        <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='800' height='600'><rect width='100%' height='100%' fill='%23e9e9e9'/><text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' fill='%23999' font-family='Arial' font-size='24'>تصویر محصول 1</text></svg>" alt="محصول 1">
        <div class="body">
          <h2 class="title">نام محصول 1</h2>
          <div class="desc">توضیح کوتاه درباره محصول — جنس، اندازه یا ویژگی اصلی.</div>
          <div class="price">قیمت: 250,000 تومان</div>
          <div class="buttons">
            <button class="btn contact" onclick="location.href='https://t.me/yourtelegramusername'">پیام در تلگرام</button>
            <button class="btn buy" onclick="window.open('https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=you@yourmail.com&item_name=Product+1&amount=250000&currency_code=USD','_blank')">خرید / پرداخت</button>
          </div>
        </div>
      </article>

      <!-- تکرار کارت برای محصولات بیشتر (کپی-پیست کنید و اطلاعات را تغییر دهید) -->
      <article class="card">
        <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='800' height='600'><rect width='100%' height='100%' fill='%23e9e9e9'/><text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' fill='%23999' font-family='Arial' font-size='24'>تصویر محصول 2</text></svg>" alt="محصول 2">
        <div class="body">
          <h2 class="title">نام محصول 2</h2>
          <div class="desc">توضیح کوتاه درباره محصول 2.</div>
          <div class="price">قیمت: 120,000 تومان</div>
          <div class="buttons">
            <button class="btn contact" onclick="location.href='mailto:you@example.com'">ایمیل</button>
            <button class="btn buy" onclick="alert('راهنمای خرید: لطفا با ما تماس بگیرید یا پیام ارسال کنید')">راهنمای خرید</button>
          </div>
        </div>
      </article>

    </section>

    <footer id="contact">
      <p>راه‌های ارتباطی: شماره تماس: ۰۵۵-۱۲۳۴۵۶۷ | تلگرام: <a href="https://t.me/yourtelegramusername">yourtelegramusername</a></p>
      <p>برای شخصی‌سازی قالب یا افزودن درگاه، من می‌تونم کمکتون کنم — بگید چه می‌خوایید.</p>
    </footer>
  </div>
</body>
</html>
