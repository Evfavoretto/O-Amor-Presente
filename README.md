<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <style>
    :root{
      --rose:#C9376E;
      --rose-2:#FCE9F0;
      --blue:#4DA6FF;
      --blue-2:#E6F3FF;
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

    .top-bar{background:var(--rose);color:#fff;text-align:center;padding:14px 10px;font-weight:900;font-size:clamp(20px,4.6vw,30px);letter-spacing:.04em;text-transform:uppercase}
    .hero{padding:28px 20px 10px;background:#fff}
    .wrap{max-width:1100px;margin:0 auto}
    .hero-card{background:#fff;border:1px solid var(--line);border-radius:22px;padding:28px 28px 34px;margin:0 auto;max-width:980px;box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center}
    .logo{max-height:170px;width:auto;margin:6px auto 10px}
    .lead{color:var(--soft);font-size:20px;text-align:center;max-width:820px;margin:12px auto 0}
    .divider{height:10px;margin:22px auto 22px;max-width:300px;border-radius:999px;background:linear-gradient(90deg,var(--rose),var(--blue))}
    .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:22px 0 0}
    .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
    .primary{background:var(--rose);color:#fff}
    .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
    section{padding:56px 20px;border-bottom:1px solid var(--line)}
    .grid{display:grid;gap:24px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}
    .section-title{font-size:clamp(30px,4.2vw,44px);font-weight:900;margin:0 0 18px;background:linear-gradient(90deg,var(--rose),var(--blue));-webkit-background-clip:text;background-clip:text;color:transparent;text-align:center}
    .grad-left{font-size:clamp(34px,4.8vw,50px);line-height:1.1;margin:0 0 12px;font-weight:900;background:linear-gradient(90deg,var(--rose) 0%, var(--blue) 100%);-webkit-background-clip:text;background-clip:text;color:transparent;text-align:left}
    p{margin:8px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}
    .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}
    .mentores{text-align:center}
    .mentores img{max-width:380px;border-radius:16px;box-shadow:0 10px 26px rgba(0,0,0,.08);margin:12px auto 6px}
    .pricing{display:grid;gap:18px}
    @media(min-width:860px){.pricing{grid-template-columns:repeat(3,1fr)}}
    .price-card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;text-align:center;box-shadow:0 10px 28px rgba(0,0,0,.05)}
    .price{font-size:40px;font-weight:900;color:var(--rose);margin:10px 0}
    .pill{display:inline-block;background:var(--blue-2);color:var(--blue);padding:6px 12px;border-radius:999px;font-weight:800;font-size:12px;margin-bottom:6px}
    .muted{color:#94a3b8}
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05)}
    .t-name{font-weight:900;margin:0 0 6px;font-size:16px}
    .woman{background:var(--rose-2);border-color:#F9C9DA}
    .man{background:var(--blue-2);border-color:#cfe7ff}
    /* FAQ */
    .faq{max-width:980px;margin:0 auto}
    .faq-item{border:1px solid var(--line);border-radius:14px;background:#fff;margin:10px 0;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.04)}
    .faq-q{width:100%;text-align:left;background:#fff;border:0;padding:16px 18px;font-size:18px;font-weight:800;color:var(--ink);cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-q .mark{flex:0 0 auto;font-weight:900;color:var(--rose)}
    .faq-a{max-height:0;overflow:hidden;transition:max-height .28s ease;border-top:1px solid var(--line)}
    .faq-a-inner{padding:16px 18px;color:var(--soft);font-size:16px}
    .faq-item.open .faq-a{max-height:360px}
    .faq-item.open .faq-q .mark{color:var(--blue)}
    /* PERGUNTA ESPECIAL */
    .special-faq{max-width:980px;margin:24px auto;border-radius:14px;overflow:hidden;box-shadow:0 8px 22px rgba(0,0,0,.08)}
    .special-q{background:var(--rose);color:#fff;font-weight:900;font-size:20px;padding:18px;text-align:center}
    .special-a{background:var(--blue);color:#fff;font-size:18px;padding:20px;text-align:center}
    .footer-cta{background:var(--blue-2);border:1px solid #dbeafe;border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between}
    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}
    .whats-float{position:fixed;right:40px;top:50%;transform:translateY(-50%);z-index:1000;width:60px;height:60px;border-radius:50%;background:#25D366;box-shadow:0 12px 28px rgba(0,0,0,.18);display:flex;align-items:center;justify-content:center}
    .whats-float svg{width:30px;height:30px;fill:#fff}
  </style>
</head>
<body>

  <div class="top-bar">Vivência de Casais</div>

  <!-- hero / logo -->
  <div class="hero"><div class="wrap"><div class="hero-card">
    <img src="logo.png" alt="Logo O Amor Presente" class="logo">
    <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”.</strong></p>
    <div class="divider"></div>
  </div></div></div>

  <!-- aqui viriam as outras seções (o que é, resultados, mentores, preços, depoimentos etc.) -->

  <!-- FAQ -->
  <section id="faq">
    <div class="wrap">
      <h2 class="section-title">Perguntas Frequentes</h2>
      <div class="faq">
        <div class="faq-item">
          <button class="faq-q"><span>Para quem é a vivência?</span><span class="mark">+</span></button>
          <div class="faq-a"><div class="faq-a-inner">Para casais em qualquer fase...</div></div>
        </div>
        <!-- outras perguntas aqui -->
      </div>
    </div>
  </section>

  <!-- PERGUNTA ESPECIAL -->
  <div class="special-faq">
    <div class="special-q">Qual é o verdadeiro propósito desta vivência?</div>
    <div class="special-a">Resgatar o amor consciente: olhar um para o outro com respeito, presença e compromisso renovado, fortalecendo o vínculo para além da rotina.</div>
  </div>

  <footer>© O Amor Presente — Vivência de Casais. Todos os direitos reservados.</footer>

  <a class="whats-float" href="https://wa.me/5549998110445?text=Quero%20saber%20mais" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Z"/></svg>
  </a>

  <script>
    const items = document.querySelectorAll('.faq-item');
    items.forEach((item) => {
      const btn = item.querySelector('.faq-q');
      const panel = item.querySelector('.faq-a');
      btn.addEventListener('click', () => {
        items.forEach(i => {
          if(i !== item) i.classList.remove('open');
        });
        item.classList.toggle('open');
      });
    });
  </script>
</body>
</html>
