<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>O Amor Presente — Vivência de Casais</title>
<meta name="description" content="Vivência de Casais — um encontro para reconectar, comunicar e fortalecer o compromisso consciente.">
<style>
  /* Oculta títulos injetados do GitHub Pages */
  .site-header,.page-header,
  header .project-name,header .site-title,
  h1.project-name,h1.site-title { display:none !important; }

  :root{
    --rose:#C9376E;
    --rose-10:#FDE7F1;
    --blue:#43A5FF;
    --blue-10:#E8F3FF;
    --ink:#0F172A;
    --soft:#667085;
    --line:#E9EEF5;
    --bg:#FFFFFF;
    --success:#10B981;
  }

  *{box-sizing:border-box}
  html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
    font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
  img{max-width:100%;display:block}
  a{text-decoration:none}

  .wrap{max-width:1100px;margin:0 auto;padding:22px}

  /* HERO */
  .hero{padding:28px 0 12px;background:linear-gradient(135deg, rgba(201,55,110,.06), rgba(67,165,255,.06))}
  .hero-card{background:#fff;border:1px solid var(--line);border-radius:22px;
    padding:26px 26px 30px;margin:0 auto;max-width:980px;box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center}
  .tag{display:inline-block;background:var(--blue-10);color:#1d4ed8;font-weight:900;
    font-size:16px;letter-spacing:.08em;text-transform:uppercase;padding:10px 18px;border-radius:999px;margin-bottom:14px}
  .logo{width:min(520px,90vw);margin:0 auto 12px} /* LOGO MAIOR */
  .lead{color:var(--soft);font-size:22px;text-align:center;max-width:820px;margin:14px auto 0}
  .divider{height:10px;margin:22px auto 20px;max-width:280px;border-radius:999px;
    background:linear-gradient(90deg,var(--rose),var(--blue))}

  /* Seções */
  section{padding:56px 0;border-bottom:1px solid var(--line)}
  .grid{display:grid;gap:24px}
  .two{grid-template-columns:1fr}
  @media(min-width:860px){ .two{grid-template-columns:1fr 1fr} }

  h2{font-size:clamp(32px,4vw,48px);margin:0 0 14px;line-height:1.15}
  .section-title{font-size:clamp(34px,4.5vw,50px);text-align:center;margin:0 0 18px}

  p{margin:8px 0 0;font-size:18px;color:var(--soft)}
  ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
  li{margin:8px 0}

  .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
  .pill{display:inline-block;background:var(--blue-10);color:#1d4ed8;padding:8px 12px;border-radius:999px;font-weight:900;font-size:15px;margin-bottom:10px}
  .list-check li{list-style:none;padding-left:28px;position:relative}
  .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

  /* Mentores */
  .mentores{display:flex;gap:16px;align-items:center;justify-content:center;margin:16px auto 0;text-align:center}
  .mentores img{width:140px;height:140px;object-fit:cover;border-radius:16px;border:2px solid var(--line)}
  .mentores p{margin:0;color:var(--soft);font-size:16px;max-width:720px}

  /* Pricing */
  #precos h2{font-size:clamp(34px,4.5vw,50px)}
  .pricing{display:grid;gap:18px}
  @media(min-width:860px){ .pricing{grid-template-columns:repeat(3,1fr)} }
  .price-card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;text-align:center;box-shadow:0 10px 28px rgba(31,35,48,.05)}
  .price-card .pill{background:var(--rose-10);color:var(--rose)}
  .price{font-size:42px;font-weight:900;color:var(--rose);margin:10px 0}

  /* Depoimentos */
  #depoimentos h2{font-size:clamp(34px,4.5vw,50px)}
  .testimonials{display:grid;gap:18px;max-width:980px;margin:0 auto}
  @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
  .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05)}
  .t-name{font-weight:900;margin:0 0 6px;font-size:17px}
  .t-text{margin:0;color:#1f2937;font-size:18px;line-height:1.55}
  .t-f{background:var(--rose-10);border-color:#F9C9DA}
  .t-f .t-name{color:var(--rose)}
  .t-m{background:var(--blue-10);border-color:#cfe7ff}
  .t-m .t-name{color:var(--blue)}

  /* Botões */
  .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:20px 0 0}
  .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
  .primary{background:var(--rose);color:#fff}
  .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}

  /* Botão WhatsApp flutuante (meio da tela) */
  .whats-float{
    position:fixed; right:18px; top:50%; transform:translateY(-50%);
    z-index:1000;width:60px;height:60px;border-radius:50%;
    background:linear-gradient(135deg,#25D366,#1EBE57);
    box-shadow:0 12px 28px rgba(0,0,0,.18);
    display:flex;align-items:center;justify-content:center
  }
  .whats-float svg{width:30px;height:30px;fill:#fff}
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="wrap">
    <div class="hero-card">
      <span class="tag">VIVÊNCIA DE CASAIS</span>
      <img src="logo1.png" alt="Logo O Amor Presente" class="logo">
      <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”</strong></p>
    </div>
  </div>
</div>

<!-- O QUE É -->
<section>
  <div class="wrap">
    <h2>O QUE É?</h2>
    <p>Um encontro imersivo para casais cuidarem do vínculo: diálogo, respeito, afeto e recomeço.</p>
  </div>
</section>

<!-- RESULTADOS -->
<section>
  <div class="wrap">
    <h2>RESULTADOS</h2>
    <ul class="list-check">
      <li>Reconexão emocional;</li>
      <li>Comunicação respeitosa;</li>
      <li>Ressignificação de feridas;</li>
      <li>Compromisso consciente.</li>
    </ul>
  </div>
</section>

<!-- INVESTIMENTO -->
<section id="precos">
  <div class="wrap">
    <h2>Investimento (por casal)</h2>
    <div class="pricing">
      <div class="price-card"><div class="pill">1º Lote</div><div class="price">R$ 620,00</div></div>
      <div class="price-card"><div class="pill">2º Lote</div><div class="price">R$ 800,00</div></div>
      <div class="price-card"><div class="pill">3º Lote</div><div class="price">R$ 998,00</div></div>
    </div>
  </div>
</section>

<!-- DEPOIMENTOS -->
<section id="depoimentos">
  <div class="wrap">
    <h2>Depoimentos</h2>
    <div class="testimonials">
      <div class="t-card t-f"><p class="t-name">Grasiela</p><p class="t-text">Olhar mais para nós como casal...</p></div>
      <div class="t-card t-m"><p class="t-name">Mateus</p><p class="t-text">Aprendi mais sobre as linguagens do amor...</p></div>
      <!-- Continue alternando F/M como antes -->
    </div>
  </div>
</section>

<footer style="background:var(--rose);color:#fff;padding:18px;text-align:center">
  © O Amor Presente — Vivência de Casais. Todos os direitos reservados.
</footer>

<!-- Botão WhatsApp -->
<a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia" target="_blank" rel="noopener">
  <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Z"/></svg>
</a>

</body>
</html>
