<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <meta name="description" content="Vivência de Casais O Amor Presente — um dia inteiro para reconectar, comunicar, ressignificar e fortalecer o compromisso consciente." />
  <style>
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

    /* Faixa Rosa cobrindo tudo no topo */
    header{
      background:var(--rose);
      color:#fff;
      padding:140px 0 80px; /* aumentamos bastante para cobrir o título azul */
      text-align:center;
      position:relative;
      overflow:hidden;
    }
    .logo{max-width:300px;margin-bottom:20px}
    .badge{
      display:inline-block;
      background:rgba(255,255,255,.15);
      backdrop-filter: blur(6px);
      border:1px solid rgba(255,255,255,.25);
      color:#fff;
      padding:8px 14px;
      border-radius:999px;
      font-size:15px;
      margin-top:16px;
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

    <section id="sobre" style="background:var(--rose-2);borde
