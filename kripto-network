<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coin Demo</title>
<style>
  /* Reset və bünövrə */
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
  body { background-color: #0d0d0d; color: #fff; }
  a { text-decoration: none; color: inherit; }
  
  /* Header */
  header { background: #111; padding: 20px 0; text-align: center; position: sticky; top: 0; z-index: 1000; }
  header h1 { color: #ff6600; font-size: 28px; }
  nav { margin-top: 10px; display: flex; justify-content: center; gap: 30px; }
  nav a { color: #fff; font-weight: bold; transition: 0.3s; }
  nav a:hover { color: #ff6600; }

  /* Hero */
  .hero { display: flex; flex-direction: column; align-items: center; justify-content: center; height: 450px; background: url('https://via.placeholder.com/1200x450') center/cover no-repeat; text-align: center; }
  .hero h2 { font-size: 48px; color: #ff6600; margin-bottom: 20px; animation: fadeInDown 1s ease forwards; opacity: 0; }
  .hero p { font-size: 20px; color: #fff; margin-bottom: 20px; animation: fadeInUp 1s 0.5s ease forwards; opacity: 0; }
  .hero button { padding: 12px 25px; background: #ff6600; border: none; border-radius: 6px; cursor: pointer; font-weight: bold; transition: 0.3s; animation: fadeInUp 1s 1s ease forwards; opacity: 0; }
  .hero button:hover { background: #ff8533; }

  /* Sections */
  .section { padding: 70px 20px; text-align: center; }
  .section h3 { font-size: 32px; margin-bottom: 25px; color: #ff6600; }
  .section p { font-size: 18px; max-width: 900px; margin: 0 auto; line-height: 1.6; }

  /* Cards */
  .cards { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 40px; }
  .card { background: #1a1a1a; padding: 20px; border-radius: 10px; width: 250px; transition: 0.3s; }
  .card:hover { transform: translateY(-10px); box-shadow: 0 10px 20px rgba(255,102,0,0.5); }
  .card h4 { color: #ff6600; margin-bottom: 10px; }
  .card p { font-size: 16px; }

  /* Footer */
  footer { background: #111; padding: 25px; text-align: center; font-size: 14px; }

  /* Animations */
  @keyframes fadeInDown { 0% { opacity:0; transform: translateY(-20px); } 100% { opacity:1; transform: translateY(0); } }
  @keyframes fadeInUp { 0% { opacity:0; transform: translateY(20px); } 100% { opacity:1; transform: translateY(0); } }

  /* Responsive */
  @media(max-width: 768px) { .cards { flex-direction: column; align-items: center; } }
</style>
</head>
<body>

<header>
  <h1>Coin Demo</h1>
  <nav>
    <a href="#about">Haqqında</a>
    <a href="#services">Xidmətlər</a>
    <a href="#contact">Əlaqə</a>
  </nav>
</header>

<section class="hero">
  <h2>Kripto Demo Sayt</h2>
  <p>Bu sayt GitHub Pages üzərində işləyən demo üçün hazırlanıb.</p>
  <button onclick="alert('Demo düyməsinə kliklədiniz!')">Daha Ətraflı</button>
</section>

<section class="section" id="about">
  <h3>Haqqında</h3>
  <p>Bu demo sayt sadə HTML, CSS və JavaScript istifadə edilərək hazırlanmışdır. Məqsəd görünüşcə hazır dizayn təqdim etməkdir. Sayt GitHub Pages üzərində işləyir və birbaşa linkdən baxa bilərsiz.</p>
</section>

<section class="section" id="services">
  <h3>Xidmətlərimiz</h3>
  <div class="cards">
    <div class="card">
      <h4>Kripto Analiz</h4>
      <p>Ən son bazar tendensiyaları və analizləri.</p>
    </div>
    <div class="card">
      <h4>Portfel İdarəetməsi</h4>
      <p>Kripto portfelinizi sadə və təhlükəsiz idarə edin.</p>
    </div>
    <div class="card">
      <h4>Trendlər</h4>
      <p>Ən son trendləri və xəbərləri izləyin.</p>
    </div>
  </div>
</section>

<section class="section" id="contact">
  <h3>Əlaqə</h3>
  <p>Email: demo@coin.com | Telefon: +994 50 000 00 00</p>
</section>

<footer>
  &copy; 2026 Coin Demo. Bütün hüquqlar qorunur.
</footer>

</body>
</html>
