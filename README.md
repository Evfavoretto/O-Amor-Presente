<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>O Amor Presente — Vivência de Casais</title>
<meta name="description" content="Vivência de Casais — um encontro para reconectar, comunicar e fortalecer o compromisso consciente.">
<style>
  /* Cobre/oculta qualquer título injetado pelo GitHub Pages */
  .site-header,.page-header,
  header .project-name,header .site-title,
  h1.project-name,h1.site-title,
  .header, .AppHeader, .gh-header, .markdown-body > h1:first-child {
    display:none !important;
  }

  :root{
    --rose:#C9376E;   /* rosa da logo */
    --rose-10:#FDE7F1;
    --blue:#43A5FF;   /* azul claro da logo */
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

  /* HERO – badge + logo BEM maior em cartão branco */
  .hero{padding:28px 0 12px;background:linear-gradient(135deg, rgba(201,55,110,.06), rgba(67,165,255,.06))}
  .hero-card{
    background:#fff;border:1px solid var(--line);border-radius:22px;
    padding:26px 26px 30px;margin:0 auto;max-width:980px;
    box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center
  }
  .tag{display:inline-block;background:var(--blue-10);color:#1d4ed8;border:1px solid #dbeafe;
    font-weight:900;font-size:13px;letter-spacing:.08em;text-transform:uppercase;
    padding:8px 14px;border-radius:999px;margin-bottom:14px}
  .logo{width:min(420px,80vw);margin:0 auto 8px} /* LOGO AINDA MAIOR */
  .lead{color:var(--soft);font-size:20px;text-align:center;max-width:820px;margin:12px auto 0}
  .divider{height:10px;margin:22px auto 20px;max-width:280px;border-radius:999px;
    background:linear-gradient(90deg,var(--rose),var(--blue))}

  /* Seções */
  section{padding:56px 0;border-bottom:1px solid var(--line)}
  .grid{display:grid;gap:24px}
  .two{grid-template-columns:1fr}
  @media(min-width:860px){ .two{grid-template-columns:1fr 1fr} }

  /* Títulos mais destacados */
  h2{font-size:clamp(28px,3.6vw,40px);margin:0 0 14px;line-height:1.15}
  .section-title{font-size:clamp(30px,4vw,44px);text-align:center;margin:0 0 18px}

  p{margin:8px 0 0;font-size:18px;color:var(--soft)}
  ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
  li{margin:8px 0}

  .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
  .pill{display:inline-block;background:var(--blue-10);color:#1d4ed8;padding:8px 12px;border-radius:999px;font-weight:900;font-size:13px;margin-bottom:10px}
  .kicker{font-weight:900;color:var(--rose);letter-spacing:.08em;text-transform:uppercase;font-size:12px}
  .list-check li{list-style:none;padding-left:28px;position:relative}
  .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:900}

  /* Mentores */
  .mentores{display:flex;gap:16px;align-items:center;justify-content:center;margin:16px auto 0;text-align:center}
  .mentores img{width:120px;height:120px;object-fit:cover;border-radius:16px;border:2px solid var(--line)}
  .mentores p{margin:0;color:var(--soft);font-size:16px;max-width:720px}

  /* Pricing (título maior) */
  #precos h2{font-size:clamp(30px,4vw,44px)}
  .pricing{display:grid;gap:18px}
  @media(min-width:860px){ .pricing{grid-template-columns:repeat(3,1fr)} }
  .price-card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;text-align:center;box-shadow:0 10px 28px rgba(31,35,48,.05)}
  .price-card .pill{background:var(--rose-10);color:var(--rose)}
  .price{font-size:40px;font-weight:900;color:var(--rose);margin:10px 0}
  .muted{color:#94a3b8}

  /* Depoimentos (título maior + alternância F/M) */
  #depoimentos h2{font-size:clamp(30px,4vw,44px)}
  .testimonials{display:grid;gap:18px;max-width:980px;margin:0 auto}
  @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
  .t-card{border:1px solid var(--line);border-radius:16px;padding:16px 18px;box-shadow:0 8px 22px rgba(0,0,0,.05)}
  .t-name{font-weight:900;margin:0 0 6px;font-size:16px}
  .t-text{margin:0;color:#1f2937;font-size:17.5px;line-height:1.55}
  /* Mulher = rosa; Homem = azul */
  .t-f{background:var(--rose-10);border-color:#F9C9DA}
  .t-f .t-name{color:var(--rose)}
  .t-m{background:var(--blue-10);border-color:#cfe7ff}
  .t-m .t-name{color:var(--blue)}

  /* CTA */
  .cta{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;margin:20px 0 0}
  .btn{display:inline-block;padding:14px 20px;border-radius:14px;font-weight:900;box-shadow:0 8px 18px rgba(0,0,0,.08)}
  .primary{background:var(--rose);color:#fff}
  .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
  .primary:hover{filter:brightness(1.05)}
  .ghost:hover{background:var(--blue);color:#fff}

  /* Botão flutuante de WhatsApp */
  .whats-float{
    position:fixed; right:18px; bottom:18px; z-index:1000;
    width:60px; height:60px; border-radius:50%;
    background:linear-gradient(135deg,#25D366,#1EBE57);
    box-shadow:0 12px 28px rgba(0,0,0,.18);
    display:flex; align-items:center; justify-content:center;
  }
  .whats-float svg{width:30px; height:30px; fill:#fff}
  .whats-float:active{transform:scale(.98)}

  /* Rodapé rosa */
  footer{padding:22px 0 28px;text-align:center;background:var(--rose);color:#fff;font-size:14px;border-top:1px solid var(--rose)}
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="wrap">
    <div class="hero-card">
      <span class="tag">Vivência de Casais</span>
      <img src="logo1.png" alt="Logo O Amor Presente" class="logo">
      <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”</strong> — um dia para olhar, ouvir e reescolher o vínculo com presença.</p>
      <div class="divider" aria-hidden="true"></div>

      <div class="grid two">
        <!-- O QUE É (título maior e claro) -->
        <div class="card">
          <span class="pill">O que é</span>
          <h2>Essência da vivência</h2>
          <p>Um encontro acolhedor, com dinâmicas simples e conversa sincera, para cuidar do que sustenta o amor: presença, respeito e verdade.</p>
        </div>
        <!-- RESULTADOS (título maior) -->
        <div class="card">
          <span class="pill">Resultados</span>
          <h2>O que vocês levam</h2>
          <ul class="list-check">
            <li><strong>Reconexão emocional</strong> e leveza;</li>
            <li><strong>Comunicação respeitosa</strong> e clara;</li>
            <li><strong>Ressignificação de feridas</strong> e aprendizados;</li>
            <li><strong>Compromisso consciente</strong> no dia a dia.</li>
          </ul>
        </div>
      </div>

      <div class="mentores">
        <img src="evandro-alinne.jpg" alt="Evandro e Alinne">
        <p><strong>Evandro & Alinne</strong> — mentores da vivência, com olhar sistêmico e acolhedor para fortalecer a parceria.</p>
      </div>

      <div class="cta">
        <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
        <a href="#inscricao" class="btn primary">Quero participar</a>
      </div>
    </div>
  </div>
</div>

<!-- INVESTIMENTO (título maior) -->
<section id="precos">
  <div class="wrap">
    <h2 class="section-title">Investimento (por casal)</h2>
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
  </div>
</section>

<!-- DEPOIMENTOS (F, M, F, M, F, M, F, M, F, F) - título maior -->
<section id="depoimentos">
  <div class="wrap">
    <h2 class="section-title">Depoimentos</h2>
    <div class="testimonials">
      <!-- 1 F -->
      <div class="t-card t-f"><p class="t-name">Grasiela Nardino</p><p class="t-text">Hoje percebi que devemos olhar mais para nós como casal, apoiar e ouvir a opinião do outro e sempre levar em consideração ambas as colocações. Em sintonia podemos crescer e evoluir muito mais.</p></div>
      <!-- 2 M -->
      <div class="t-card t-m"><p class="t-name">Mateus Battistela</p><p class="t-text">Hoje valeu a pena porque aprendi um pouco mais sobre nosso relacionamento, as linguagens do amor e a importância de saber ouvir e se apoiar.</p></div>
      <!-- 3 F -->
      <div class="t-card t-f"><p class="t-name">Alini De Paris</p><p class="t-text">A comunicação clara e expressiva, respeitando o tempo e a individualidade do outro, cria um ambiente mais seguro e acolhedor, fortalecendo nossa conexão emocional.</p></div>
      <!-- 4 M -->
      <div class="t-card t-m"><p class="t-name">Jean Camargo</p><p class="t-text">Percebi que precisamos cultivar amor próprio para depois oferecer na relação, em sintonia na comunicação e escutando com amor — cultivando boas raízes.</p></div>
      <!-- 5 F -->
      <div class="t-card t-f"><p class="t-name">Joice</p><p class="t-text">Uma experiência única que superou as expectativas. Precisamos cuidar do nosso casamento para vivermos de maneira leve e feliz.</p></div>
      <!-- 6 M -->
      <div class="t-card t-m"><p class="t-name">Marcelo Pissaia Novo</p><p class="t-text">Devemos olhar para quem está ao nosso lado com amor e respeito, nos apoiar nos momentos difíceis e nunca largar a mão.</p></div>
      <!-- 7 F -->
      <div class="t-card t-f"><p class="t-name">Ivete</p><p class="t-text">Valeu a pena o encontro de casal para entender um ao outro, apoiar sempre, tirar as dores e cuidar das nossas raízes.</p></div>
      <!-- 8 M -->
      <div class="t-card t-m"><p class="t-name">Valdemar</p><p class="t-text">Senti a necessidade de buscar mais apoio quando o casal está com dores.</p></div>
      <!-- 9 F -->
      <div class="t-card t-f"><p class="t-name">Roselei Teles</p><p class="t-text">Um relacionamento saudável é baseado em confiança, em si mesma e no outro; compreender as dores e respeitar o momento de cada um.</p></div>
      <!-- 10 F -->
      <div class="t-card t-f"><p class="t-name">Claudete</p><p class="t-text">Importante a confiança e o compartilhamento de sonhos e projetos. Condução e responsabilidade caminham juntas.</p></div>
    </div>
  </div>
</section>

<!-- CTA final -->
<section id="inscricao" style="padding:32px 0">
  <div class="wrap" style="text-align:center">
    <p style="margin:0 0 12px;color:var(--soft)">Vagas limitadas • 08h às 17h • <em>Data & Local a confirmar</em></p>
    <a href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20na%20Viv%C3%AAncia%20O%20Amor%20Presente" class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>
  </div>
</section>

<footer>
  <div class="wrap">© O Amor Presente — Vivência de Casais. Todos os direitos reservados.</div>
</footer>

<!-- Botão flutuante de WhatsApp -->
<a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
  <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
</a>

</body>
</html>
