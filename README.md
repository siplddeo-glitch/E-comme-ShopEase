# E-comme-ShopEase
ShopEase – Your one-stop online store for fashion, electronics, and essentials. Enjoy secure shopping, best deals, and fast delivery — all in one place!
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ShopEase — Smart Shopping Made Simple</title>
  <meta name="description" content="ShopEase – Your one-stop online store for fashion, electronics, and essentials. Enjoy secure shopping, best deals, and fast delivery — all in one place!" />
  <!-- Structured data for SEO & author -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "ShopEase",
    "url": "https://example.com",
    "description": "ShopEase – Your one-stop online store for fashion, electronics, and essentials. Enjoy secure shopping, best deals, and fast delivery — all in one place!",
    "author": {
      "@type": "Person",
      "name": "Amos Anand",
      "jobTitle": "Web Developer"
    }
  }
  </script>

  <style>
    :root{
      --bg: #f7fafc;
      --card: #ffffff;
      --accent: #0b79d0;
      --text: #0f172a;
      --muted: #64748b;
      --radius: 14px;
      --maxw: 820px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:linear-gradient(180deg, #eef2f7 0%, var(--bg) 100%);
      color:var(--text);
      display:flex;
      align-items:center;
      justify-content:center;
      min-height:100vh;
      padding:28px;
    }
    .card{
      background:var(--card);
      border-radius:var(--radius);
      box-shadow: 0 8px 30px rgba(15,23,42,0.08);
      max-width:var(--maxw);
      width:100%;
      padding:28px;
      display:grid;
      gap:18px;
    }
    .brand {
      display:flex;
      align-items:center;
      gap:12px;
    }
    .logo {
      width:56px;
      height:56px;
      border-radius:10px;
      display:inline-grid;
      place-items:center;
      font-weight:700;
      color:#fff;
      background:linear-gradient(135deg,#0b79d0,#0b9bd0);
      box-shadow: 0 6px 18px rgba(11,121,208,0.18);
    }
    h1{
      margin:0;
      font-size:20px;
      letter-spacing:0.2px;
    }
    .tagline{
      margin:0;
      font-size:18px;
      line-height:1.35;
      color:var(--muted);
    }
    .meta{
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:12px;
      margin-top:6px;
      font-size:13px;
      color:var(--muted);
    }
    .author{
      display:flex;
      gap:10px;
      align-items:center;
    }
    .author .dot{
      width:36px;
      height:36px;
      border-radius:50%;
      background:#e6eef9;
      display:inline-grid;
      place-items:center;
      font-weight:600;
      color:#0b79d0;
    }
    @media (max-width:520px){
      .card{padding:18px}
      h1{font-size:18px}
      .tagline{font-size:16px}
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-labelledby="site-title">
    <div class="brand" aria-hidden="true">
      <div class="logo">SE</div>
      <div>
        <h1 id="site-title">ShopEase</h1>
        <div class="meta">Smart Shopping Made Simple</div>
      </div>
    </div>

    <!-- Two-line tagline (kept short & prominent) -->
    <p class="tagline" aria-label="tagline">
      ShopEase – Your one-stop online store for fashion, electronics, and essentials.<br />
      Enjoy secure shopping, best deals, and fast delivery — all in one place!
    </p>

    <!-- Author / developer credit -->
    <footer class="meta" aria-label="author">
      <div class="author">
        <div class="dot" aria-hidden="true">AA</div>
        <div>
          <div><strong>Amos Anand</strong></div>
          <div style="font-size:13px;color:var(--muted)">Web Developer</div>
        </div>
      </div>

      <div style="font-size:13px;color:var(--muted)">
        <time datetime="2025-10-17">Oct 17, 2025</time>
      </div>
    </footer>
  </main>
</body>
</html>
