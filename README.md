<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <meta name="description" content="Vivência de Casais O Amor Presente — um dia inteiro para reconectar, comunicar, ressignificar e fortalecer o compromisso consciente." />
  <style>
    /* Forçar remoção do título azul padrão do GitHub Pages */
    header .project-name,
    header .site-title,
    h1.project-name,
    h1.site-title {
      display: none !important;
    }

    :root{
      --rose:#C9376E;
      --rose-2:#fce9f0;
      --blue:#4DA6FF;
      --blue-light:#e6f3ff;
      --ink:#1f2330;
      --soft:#6b7280;
      --bg:#fff;
      --success:#10B981;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,'Helvetica Neue',Arial}
    a{color:var(--rose);text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:24px}

    /* Header */
    header{
      background:linear-gradient(135deg,var(--rose) 0%, var(--blue) 100%);
      color:#fff;
      padding:100px 0 72px;
      text-align:center;
      position:relative;
      overflow:hidden;
    }
    header .container{position:relative;z-index:2}
    .logo{max-width:280px;margin-bottom:20px}
    .badge{
      display:inline-block;
      background:rgba(255,255,255,.15);
      backdrop-filter: blur(6px);
      border:1px solid rgba(255,255,255,.25);
      color:#fff;
      padding:8px 14px;
      border-radius:999px;
      font-size:15px;
      margin-bottom:16px;
      font-weight:600;
    }
    .subtitle{font-size:clamp(16px,2.8vw,22px);opacity:.95;max-width:780px;margin:0 auto}

    /* CTA */
    .cta-wrap{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:28px}
    .btn{display:inline-block;padding:14px 20px;border-radius:12px;font-weight:600;transition:.2s ease;box-shadow:0 6px 14px rgba(0,0,0,.12)}
    .btn-primary{background:#fff;color:var(--rose)}
    .btn-primary:hover{transform:translateY(-1px)}
    .btn-outline{border:2px solid #fff;color:#fff}
    .btn-outline:hover{background:rgba(255,255,255,.12)}

    section{padding:56px 0;border-bottom:1px solid #f1f5f9}
    .grid{display:grid;gap:22px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){ .two{grid-template-columns:1fr 1fr} }

    h2{font-size:clamp(24px,3.8vw,34px);margin:0 0 16px;font-weight:700}
    p{margin:10px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}

    /* Cards */
    .card{
      background:#fff;
      border:1px solid #e5e7eb;
      border-radius:16px;
      padding:22px;
      box-shadow:0 8px 24px rgba(31,35,48,.06);
    }
    .pill{display:inline-block;background:var(--blue-light);color:var(--blue);padding:4px 10px;border-radius:999px;font-weight:600;font-size:13px;margin-bottom:8px}

    /* Pricing */
    .pricing{display:grid;grid-template-columns:1fr;gap:16px}
    @media(min-width:860px){ .pricing{grid-template-columns:repeat(3,1fr)} }
    .price-card{background:#fff;border:1px solid #e5e7eb;border-radius:16px;padding:22px;text-align:center}
    .price{font-size:34px;font-weight:800;color:var(--rose);margin:8px 0}
    .muted{color:#64748b}

    /* Footer CTA */
    .footer-cta{
      background:var(--blue-light);
      border:1px solid #dbeafe;
      border-radius:16px;
      padding:26px;
      display:flex;gap:16px;flex-wrap:wrap;
      align-items:center;justify-content:space-between
    }
    footer{padding:40px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    .kicker{font-weight:700;color:var(--rose);letter-spacing:.08em;text-transform:uppercase;font-size:12px}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:800}

    /* Depoimentos */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{background:#fff;border:1px solid #e5e7eb;border-radius:16px;padding:16px;
      box-shadow:0 8px 24px rgba(31,35,48,.05)}
    .t-name{font-weight:800;margin:0 0 6px;font-size:16px;color:var(--ink)}
    .t-text{margin:0;color:var(--ink);font-size:17px;line-height:1.45}

    /* Botão WhatsApp */
    .whatsapp-float {
      position: fixed;
      bottom: 50%;
      right: 20px;
      transform: translateY(50%);
      background: #25D366;
      color: #fff;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 4px 12px rgba(0,0,0,.15);
      z-index: 1000;
    }
    .whatsapp-float img {
      width: 32px;
      height: 32px;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <img src="logo.png" alt="Logo O Amor Presente" class="logo">
      <div class="badge">VIVÊNCIA DE CASAIS</div>
      <p class="subtitle"><strong>“Reconectar: A Linguagem do Amor em Movimento”</strong> — um dia para olhar, ouvir e resolver o vínculo com presença.</p>
      <div class="cta-wrap">
        <a href="#inscricao" class="btn btn-primary">Quero Participar</a>
        <a href="#como-sera" class="btn btn-outline">Como será o dia?</a>
      </div>
    </div>
  </header>

  <main class="container">

    <section id="sobre" style="background:var(--rose-2);border-radius:12px;padding:40px;margin-top:30px">
      <h2 style="background: linear-gradient(90deg, var(--rose), var(--blue));-webkit-background-clip:text;-webkit-text-fill-color:transparent;font-size:36px">O que é a vivência?</h2>
      <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado. Aqui, vocês vão se olhar de novo, se ouvir de verdade e reencontrar o amor como escolha diária.</p>
    </section>

    <section id="resultados" style="margin-top:40px">
      <h2 style="background: linear-gradient(90deg, var(--blue), var(--rose));-webkit-background-clip:text;-webkit-text-fill-color:transparent;font-size:36px">Resultados</h2>
      <ul class="list-check">
        <li><strong>Reconexão emocional e leveza</strong></li>
        <li><strong>Comunicação respeitosa e clara</strong></li>
        <li><strong>Ressignificação de feridas e aprendizados</strong></li>
        <li><strong>Compromisso consciente no dia a dia</strong></li>
      </ul>
    </section>

    <section id="precos">
      <h2>Investimento (por casal)</h2>
      <div class="pricing">
        <div class="price-card">
          <div class="pill">1º Lote</div>
          <div class="price">R$ 620,00</div>
          <p class="muted">Vagas limitadas</p>
        </div>
        <div class="price-card">
          <div class="pill">2º Lote</div>
          <div class="price">R$ 800,00</div>
          <p class="muted">Sujeito à disponibilidade</p>
        </div>
        <div class="price-card">
          <div class="pill">3º Lote</div>
          <div class="price">R$ 998,00</div>
          <p class="muted">Últimas vagas</p>
        </div>
      </div>
    </section>

    <section id="depoimentos" style="background:var(--blue-light);border-radius:12px;padding:40px;margin-top:40px">
      <h2>Depoimentos</h2>
      <div class="testimonials">
        <div class="t-card"><p class="t-name" style="color:var(--rose)">Grasiela Nardino</p><p class="t-text">Hoje percebi que devemos olhar mais para nós como casal, apoiar e ouvir a opinião do outro...</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--blue)">Mateus Battistela</p><p class="t-text">Hoje valeu a pena porque aprendi um pouco mais sobre nosso relacionamento, as linguagens do amor...</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--rose)">Alini De Paris</p><p class="t-text">Hoje valeu a pena porque a comunicação clara e expressiva em um relacionamento é muito importante...</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--blue)">Marcelo Pissaia Novo</p><p class="t-text">Hoje percebi que devemos olhar para a pessoa que está ao nosso lado com amor e respeito...</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--rose)">Joice</p><p class="t-text">A vivência de hoje foi mais uma vez, uma experiência única que superou as expectativas...</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--blue)">Valdemar & Ivete</p><p class="t-text">Valeu a pena porque senti a necessidade de buscar mais apoio quando o casal está com dores.</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--rose)">Ivete</p><p class="t-text">Hoje percebi que valeu a pena o encontro de casal para entender um ao outro, apoiar sempre, tirar as dores e cuidar das nossas raízes.</p></div>
        <div class="t-card"><p class="t-name" style="color:var(--blue)">Jean Camargo</p><p class="t-text">Hoje percebi que devemos cultivar amor próprio primordialmente para depois oferecer na relação...</p></div>
      </div>
    </section>

    <section id="inscricao" style="text-align:center;margin:50px 0">
      <h2>Garanta sua vaga</h2>
      <p>As vagas são limitadas. Clique no botão abaixo para iniciar sua inscrição.</p>
      <div class="cta-wrap">
        <a class="btn btn-primary" href="#" title="Link do formulário/checkout">Quero Participar</a>
        <a class="btn" style="background:var(--blue-light);color:var(--blue)" href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" target="_blank" rel="noopener">Falar no WhatsApp</a>
      </div>
    </section>

    <section>
      <div class="footer-cta">
        <div>
          <div class="kicker">Pronto para reconectar?</div>
          <h3 style="margin:6px 0 0">Um dia para lembrar, sentir e escolher novamente o amor.</h3>
        </div>
        <a href="#inscricao" class="btn btn-primary">Inscrever-se agora</a>
      </div>
    </section>

  </main>

  <footer>
    <p>© O Amor Presente — Vivência de Casais. Todos os direitos reservados.</p>
  </footer>

  <!-- Botão flutuante WhatsApp -->
  <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="whatsapp-float" target="_blank" rel="noopener">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
</body>
</html>
