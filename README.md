
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>O Amor Presente — Vivência de Casais</title>
  <meta name="description" content="Vivência de Casais O Amor Presente — um dia inteiro para reconectar, comunicar, ressignificar e fortalecer o compromisso consciente." />
  <style>
    /* Esconde título padrão do GitHub Pages */
    header .project-name, header .site-title, h1.project-name, h1.site-title { display:none !important; }

    :root{
      --rose:#C9376E;
      --rose-2:#FDE7F0;
      --blue:#4DA6FF;
      --blue-2:#E6F3FF;
      --ink:#1F2330;
      --soft:#667085;
      --bg:#ffffff;
      --success:#10B981;
      --line:#EEF2F6;
    }

    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
    img{max-width:100%;display:block}
    a{color:var(--rose);text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:24px}

    /* ===== HERO ===== */
    header{
      position:relative;
      background:linear-gradient(135deg, rgba(201,55,110,.08) 0%, rgba(77,166,255,.08) 100%);
      padding:56px 0 72px;
    }
    .hero-band{
      position:absolute; inset:0 0 auto 0; height:10px;
      background:linear-gradient(90deg, var(--rose) 0%, var(--blue) 100%);
    }
    .hero-card{
      margin:0 auto; max-width:880px; text-align:center;
      background:#fff; border:1px solid var(--line); border-radius:20px;
      padding:28px 24px 32px;
      box-shadow:0 10px 30px rgba(31,35,48,.08);
    }
    .logo{max-width:180px; margin:0 auto 14px}
    .badge{display:inline-block;background:var(--blue-2);color:#1d4ed8;border:1px solid #dbeafe;padding:8px 12px;border-radius:999px;font-size:14px;margin:8px 0 10px}
    h1{font-size:clamp(28px,5vw,44px);line-height:1.1;margin:6px 0 6px}
    .subtitle{font-size:clamp(16px,2.6vw,22px);color:var(--soft);max-width:760px;margin:0 auto}
    .cta-wrap{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:22px}
    .btn{display:inline-block;padding:14px 20px;border-radius:12px;font-weight:700;transition:.2s ease;box-shadow:0 6px 14px rgba(0,0,0,.06)}
    .btn-primary{background:var(--rose);color:#fff}
    .btn-primary:hover{transform:translateY(-1px);filter:brightness(1.02)}
    .btn-outline{border:2px solid var(--rose);color:var(--rose);background:#fff}
    .btn-outline:hover{background:var(--rose);color:#fff}

    /* ===== SEÇÕES ===== */
    section{padding:56px 0;border-bottom:1px solid var(--line)}
    .grid{display:grid;gap:22px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){ .two{grid-template-columns:1fr 1fr} }
    h2{font-size:clamp(22px,3.2vw,32px);margin:0 0 14px}
    p{margin:8px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}

    .card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:22px;box-shadow:0 8px 24px rgba(31,35,48,.04)}
    .pill{display:inline-block;background:var(--blue-2);color:#1d4ed8;padding:4px 10px;border-radius:999px;font-weight:700;font-size:12px;margin-bottom:8px}
    .kicker{font-weight:800;color:var(--rose);letter-spacing:.08em;text-transform:uppercase;font-size:12px}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

    /* Faixas suaves para respiro visual */
    .soft{background:var(--blue-2)}
    .soft-rose{background:var(--rose-2)}

    /* Pricing */
    .pricing{display:grid;grid-template-columns:1fr;gap:16px}
    @media(min-width:860px){ .pricing{grid-template-columns:repeat(3,1fr)} }
    .price-card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:22px;text-align:center}
    .price{font-size:34px;font-weight:900;color:var(--rose);margin:8px 0}
    .muted{color:#94a3b8}

    /* Depoimentos (texto + nome) */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{background:#fff;border:1px solid var(--line);border-radius:14px;padding:16px;box-shadow:0 8px 20px rgba(31,35,48,.04)}
    .t-name{font-weight:800;margin:0 0 6px;font-size:15px;color:#0f172a}
    .t-text{margin:0;color:#1f2937;font-size:17px;line-height:1.5}

    /* Instrutores */
    .mentores{display:flex;flex-direction:column;align-items:center;text-align:center}
    .mentores img{max-width:340px;border-radius:16px;margin-bottom:18px;box-shadow:0 10px 28px rgba(0,0,0,.10)}
    .mentores p{max-width:780px}

    /* Bloco final */
    .footer-cta{background:#fff;border:1px solid var(--line);border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between;box-shadow:0 8px 24px rgba(0,0,0,.05)}
    footer{padding:36px 0;color:#94a3b8;font-size:14px}
  </style>
</head>
<body>

  <header>
    <div class="hero-band" aria-hidden="true"></div>
    <div class="container">
      <!-- Cartão branco da logo/título -->
      <div class="hero-card">
        <img src="logo1.png" alt="Logo O Amor Presente" class="logo">
        <span class="badge">Vivência de Casais</span>
        <h1>O Amor Presente</h1>
        <p class="subtitle"><strong>“Reconectar: A Linguagem do Amor em Movimento”</strong> — uma jornada para reconectar emoções, renovar o vínculo e despertar a verdadeira parceria.</p>
        <div class="cta-wrap">
          <a href="#inscricao" class="btn btn-primary">Quero Participar</a>
          <a href="#como-sera" class="btn btn-outline">Como será o dia?</a>
        </div>
      </div>
    </div>
  </header>

  <main class="container">

    <section id="sobre">
      <div class="grid two">
        <div>
          <h2>O que é a vivência?</h2>
          <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado. Aqui, vocês vão se olhar de novo, se ouvir de verdade e reencontrar o amor como escolha diária.</p>
        </div>
        <div class="card">
          <span class="pill">Objetivos</span>
          <h3 class="kicker">Resultados que você leva</h3>
          <ul class="list-check">
            <li><strong>Reconexão emocional</strong>: sentir novamente o encanto do início;</li>
            <li><strong>Comunicação profunda e respeitosa</strong>;</li>
            <li><strong>Ressignificação de feridas</strong> e aprendizados;</li>
            <li><strong>Compromisso consciente</strong>: escolher amar todos os dias;</
