<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <meta name="description" content="Vivência de Casais O Amor Presente — um dia inteiro para reconectar, comunicar, ressignificar e fortalecer o compromisso consciente." />
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
      --warn:#E11D48;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
      font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
    img{max-width:100%;display:block}
    a{text-decoration:none}

    /* Esconde o título padrão do GitHub Pages */
    header .project-name,
    header .site-title,
    h1.project-name,
    h1.site-title {
      display:none !important;
    }

    /* FAIXA ROSA DE TOPO (apenas o texto) */
    .top-bar{
      background:var(--rose);
      color:#fff;
      text-align:center;
      padding:14px 10px;
      font-weight:900;
      font-size:clamp(20px,4.6vw,30px);
      letter-spacing:.04em;
      text-transform:uppercase;
    }

    /* HERO COM CARTÃO BRANCO ABAIXO DA FAIXA */
    .hero{padding:28px 20px 10px;background:#fff}
    .wrap{max-width:1100px;margin:0 auto}
    .hero-card{
      background:#fff;border:1px solid var(--line);border-radius:22px;
      padding:28px 28px 34px;margin:0 auto;max-width:980px;
      box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center
    }
    .logo{max-height:170px;width:auto;margin:6px auto 10px}
    .lead{color:var(--soft);font-size:20px;text-align:center;max-width:820px;margin:12px auto 0}
    .divider{height:10px;margin:22px auto 22px;max-width:300px;border-radius:999px;
      background:linear-gradient(90deg,var(--rose),var(--blue))}

    /* BOTÕES */
    .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:22px 0 0}
    .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
    .primary{background:var(--rose);color:#fff}
    .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
    .primary:hover{filter:brightness(1.05)}
    .ghost:hover{background:var(--blue);color:#fff}

    /* SEÇÕES */
    section{padding:56px 20px;border-bottom:1px solid var(--line)}
    .grid{display:grid;gap:24px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}

    /* TÍTULOS */
    .section-title{
      font-size:clamp(30px,4.2vw,44px);font-weight:900;margin:0 0 18px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:center;
    }
    .grad-left{
      font-size:clamp(34px,4.8vw,50px);line-height:1.1;margin:0 0 12px;font-weight:900;
      background:linear-gradient(90deg,var(--rose) 0%, var(--blue) 100%);
      -webkit-background-clip:text;background-clip:text;color:transparent;text-align:left;
    }
    p{margin:8px 0 0;font-size:18px;color:var(--soft)}
    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

    /* CARDS O QUE É / RESULTADOS */
    .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}

    /* INSTRUTORES */
    .mentores{text-align:center}
    .mentores img{max-width:380px;border-radius:16px;box-shadow:0 10px 26px rgba(0,0,0,.08);margin:12px auto 6px}

    /* PREÇOS */
    .pricing{display:grid;gap:18px}
    @media(min-width:860px){.pricing{grid-template-columns:repeat(3,1fr)}}
    .price-card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;text-align:center;box-shadow:0 10px 28px rgba(0,0,0,.05)}
    .price{font-size:40px;font-weight:900;color:var(--rose);margin:10px 0}
    .pill{display:inline-block;background:var(--blue-2);color:var(--blue);padding:6px 12px;border-radius:999px;font-weight:800;font-size:12px;margin-bottom:6px}
    .muted{color:#94a3b8}

    /* DEPOIMENTOS */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05)}
    .t-name{font-weight:900;margin:0 0 6px;font-size:16px}
    .woman{background:var(--rose-2);border-color:#F9C9DA}
    .man{background:var(--blue-2);border-color:#cfe7ff}

    /* É PARA VOCÊ / NÃO É PARA VOCÊ */
    .fit-grid{display:grid;gap:22px}
    @media(min-width:860px){.fit-grid{grid-template-columns:1fr 1fr}}
    .fit-card{
      border:1px solid var(--line);border-radius:18px;padding:22px;
      box-shadow:0 10px 26px rgba(0,0,0,.05)
    }
    .fit-yes{background:#ECFDF5}
    .fit-no{background:#FFE4EA}
    .fit-title{margin:0 0 10px;font-weight:900;font-size:clamp(22px,3.2vw,28px)}

    /* FAQ */
    .faq{max-width:980px;margin:0 auto}
    .faq-item{margin:12px 0;border-radius:14px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.06);border:1px solid var(--line)}
    .faq-q{width:100%;text-align:left;background:var(--rose);border:0;padding:16px 18px;font-size:18px;font-weight:900;color:#fff;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-q .mark{flex:0 0 auto;font-weight:900;color:#fff}
    .faq-a{max-height:0;overflow:hidden;transition:max-height .28s ease;background:var(--blue);color:#fff}
    .faq-a-inner{padding:16px 18px;font-size:16px;line-height:1.55}
    .faq-item.open .faq-a{max-height:360px}

    /* CTA FINAL + RODAPÉ */
    .footer-cta{background:var(--blue-2);border:1px solid #dbeafe;border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between}
    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    /* WHATSAPP FLUTUANTE */
    .whats-float{
      position:fixed; right:40px; top:50%; transform:translateY(-50%); z-index:1000;
      width:60px; height:60px; border-radius:50%;
      background:#25D366; box-shadow:0 12px 28px rgba(0,0,0,.18);
      display:flex; align-items:center; justify-content:center;
    }
    .whats-float svg{width:30px; height:30px; fill:#fff}
  </style>
</head>
<body>

  <!-- FAIXA ROSA -->
  <div class="top-bar">Vivência de Casais</div>

  <!-- HERO -->
  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <img src="logo.png" alt="Logo O Amor Presente" class="logo">
        <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”.</strong></p>
        <div class="divider"></div>

        <!-- O que é + Resultados -->
        <div class="grid two">
          <div class="card pink">
            <h2 class="grad-left">O que é a vivência?</h2>
            <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado.</p>
          </div>
          <div class="card blue">
            <h2 class="grad-left">Resultados</h2>
            <ul class="list-check">
              <li><strong>Reconexão emocional</strong> e leveza;</li>
              <li><strong>Comunicação respeitosa</strong> e clara;</li>
              <li><strong>Ressignificação de feridas</strong> e aprendizados;</li>
              <li><strong>Compromisso consciente</strong> no dia a dia.</li>
            </ul>
          </div>
        </div>

        <!-- Mentores -->
        <div class="mentores" style="margin-top:18px">
          <h2 class="section-title">Instrutores</h2>
          <img src="evandro-alinne.jpg" alt="Evandro & Alinne — mentores da vivência">
          <p><strong>Evandro & Alinne</strong> — mentores com olhar sistêmico e acolhedor para fortalecer a parceria.</p>
        </div>

        <!-- CTA primária -->
        <div class="cta">
          <a href="https://wa.me/5549998110445" class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
          <a href="#inscricao" class="btn primary" target="_blank" rel="noopener">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- INVESTIMENTO -->
  <section id="precos">
    <div class="wrap">
      <h2 class="section-title">Investimento (por casal)</h2>
      <div class="pricing">
        <div class="price-card"><div class="pill">1º Lote</div><div class="price">R$ 620,00</div><p class="muted">Vagas limitadas</p></div>
        <div class="price-card"><div class="pill">2º Lote</div><div class="price">R$ 800,00</div><p class="muted">Sujeito à disponibilidade</p></div>
        <div class="price-card"><div class="pill">3º Lote</div><div class="price">R$ 998,00</div><p class="muted">Últimas vagas</p></div>
      </div>
    </div>
  </section>

  <!-- DEPOIMENTOS -->
  <section id="depoimentos">
    <div class="wrap">
      <h2 class="section-title">Depoimentos</h2>
      <div class="testimonials">
        <div class="t-card woman"><p class="t-name">Grasiela Nardino</p><p>Hoje percebi que devemos olhar mais para nós como casal...</p></div>
        <div class="t-card man"><p class="t-name">Mateus Battistela</p><p>Aprendi um pouco mais sobre nosso relacionamento...</p></div>
      </div>
    </div>
  </section>

  <!-- É PARA VOCÊ / NÃO É PARA VOCÊ -->
  <section id="para-quem">
    <div class="wrap">
      <h2 class="section-title">É para você se... / Não é para você se...</h2>
      <div class="fit-grid">
        <div class="fit-card fit-yes"><h3 class="fit-title">É para você se...</h3></div>
        <div class="fit-card fit-no"><h3 class="fit-title">Não é para você se...</h3></div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="wrap">
      <h2 class="section-title">Perguntas Frequentes</h2>
      <div class="faq">
        <div class="faq-item">
          <button class="faq-q"><span>Para quem é a vivência?</span><span class="mark">+</span></button>
          <div class="faq-a"><div class="faq-a-inner">Para casais em qualquer fase.</div></div>
        </div>
      </div>
    </div>
  </section>

  <!-- INSCRIÇÃO -->
  <section id="inscricao">
    <div class="wrap" style="text-align:center">
      <p style="margin:0 0 12px;color:var(--soft)">Vagas limitadas • 08h às 17h</p>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSc7wsV5YQcTsjH9x3CSAVRu13jba3_sSbD39dFqQgxWprBqXQ/viewform" class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>
    </div>
  </section>

  <!-- RODAPÉ -->
  <footer>© O Amor Presente — Vivência de Casais. Todos os direitos reservados.</footer>

  <!-- BOTÃO FLUTUANTE WHATSAPP -->
  <a class="whats-float" href="https://wa.me/5549998110445" target="_blank" rel="noopener">
    <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Z"/></svg>
  </a>

  <!-- JS FAQ -->
  <script>
    (function(){
      const items=document.querySelectorAll('.faq-item');
      items.forEach((item)=>{const btn=item.querySelector('.faq-q');const panel=item.querySelector('.faq-a');
        btn.addEventListener('click',()=>{items.forEach(i=>{if(i!==item){i.classList.remove('open')}});item.classList.toggle('open');});});
    })();
  </script>
</body>
</html>
