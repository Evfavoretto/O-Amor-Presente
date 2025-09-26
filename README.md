<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <style>
    :root {
      --rose:#C9376E;
      --rose-light:#fce9f0;
      --blue:#4DA6FF;
      --blue-light:#e6f3ff;
      --ink:#1f2330;
      --soft:#6b7280;
      --bg:#fff;
      --success:#10B981;
    }

    body {margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Arial;color:var(--ink);background:var(--bg)}

    header {
      background:var(--rose);
      text-align:center;
      padding:160px 24px 80px; /* aumentei muito o espaço de cima */
      color:#fff;
      position:relative;
      z-index:10;
    }

    header img.logo {
      max-height:180px;
      width:auto;
      display:block;
      margin:0 auto 18px;
    }

    header .badge {
      font-size:34px;
      font-weight:700;
      text-transform:uppercase;
      letter-spacing:.06em;
    }

    section {padding:56px 20px;max-width:1100px;margin:0 auto}

    h2 {
      font-size:38px;
      margin:0 0 18px;
      background: linear-gradient(90deg, var(--rose), var(--blue));
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
    }

    p {font-size:18px;line-height:1.6;color:var(--soft)}

    .grid {display:grid;gap:22px}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}

    .card {
      border-radius:16px;
      padding:28px;
      box-shadow:0 8px 24px rgba(0,0,0,.05);
    }
    .pink {background:var(--rose-light)}
    .blue {background:var(--blue-light)}

    ul{margin:0;padding-left:20px;color:var(--soft)}
    li{margin:10px 0;font-size:18px}
    .list-check li{list-style:none;position:relative;padding-left:28px}
    .list-check li:before{content:"✓";color:var(--success);font-weight:800;position:absolute;left:0;top:0}

    /* Depoimentos */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border-radius:16px;padding:20px;box-shadow:0 8px 24px rgba(0,0,0,.05)}
    .t-name{font-weight:700;margin:0 0 8px}
    .t-text{margin:0;line-height:1.5}
    .woman{background:var(--rose-light)}
    .man{background:var(--blue-light)}

    /* Botão flutuante WhatsApp */
    .whatsapp-float {
      position:fixed;
      right:20px;
      top:50%;
      transform:translateY(-50%);
      background:#25D366;
      color:#fff;
      border-radius:50%;
      width:60px;height:60px;
      display:flex;align-items:center;justify-content:center;
      box-shadow:0 4px 12px rgba(0,0,0,.2);
      z-index:1000;
    }
    .whatsapp-float img {width:32px;height:32px}

    footer {
      background:var(--rose);
      text-align:center;
      color:#fff;
      font-size:14px;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Logo O Amor Presente" class="logo">
    <div class="badge">Vivência de Casais</div>
  </header>

  <main>
    <!-- Seção O que é e Resultados -->
    <section id="sobre">
      <div class="grid two">
        <div class="card pink">
          <h2>O que é a vivência?</h2>
          <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado. Aqui, vocês vão se olhar de novo, se ouvir de verdade e reencontrar o amor como escolha diária.</p>
        </div>
        <div class="card blue">
          <h2>Resultados</h2>
          <ul class="list-check">
            <li>Reconexão emocional e leveza;</li>
            <li>Comunicação respeitosa e clara;</li>
            <li>Ressignificação de feridas e aprendizados;</li>
            <li>Compromisso consciente no dia a dia.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Investimento -->
    <section id="precos">
      <h2>Investimento (por casal)</h2>
      <div class="grid two">
        <div class="card pink" style="text-align:center">
          <h3>1º Lote</h3>
          <p style="font-size:28px;font-weight:800;color:var(--rose)">R$ 620,00</p>
          <p>Vagas limitadas</p>
        </div>
        <div class="card blue" style="text-align:center">
          <h3>2º Lote</h3>
          <p style="font-size:28px;font-weight:800;color:var(--rose)">R$ 800,00</p>
          <p>Sujeito à disponibilidade</p>
        </div>
        <div class="card pink" style="text-align:center">
          <h3>3º Lote</h3>
          <p style="font-size:28px;font-weight:800;color:var(--rose)">R$ 998,00</p>
          <p>Últimas vagas</p>
        </div>
      </div>
    </section>

    <!-- Depoimentos -->
    <section id="depoimentos">
      <h2>Depoimentos</h2>
      <div class="testimonials">
        <div class="t-card woman"><p class="t-name">Grasiela Nardino</p><p class="t-text">Hoje percebi que devemos olhar mais para nós como casal...</p></div>
        <div class="t-card man"><p class="t-name">Mateus Battistela</p><p class="t-text">Hoje valeu a pena porque aprendi um pouco mais sobre nosso relacionamento...</p></div>
        <div class="t-card woman"><p class="t-name">Alini De Paris</p><p class="t-text">Hoje valeu a pena porque a comunicação clara e expressiva em um relacionamento é muito importante...</p></div>
        <div class="t-card man"><p class="t-name">Marcelo Pissaia Novo</p><p class="t-text">Hoje percebi que devemos olhar para a pessoa que está ao nosso lado com amor e respeito...</p></div>
        <div class="t-card woman"><p class="t-name">Joice</p><p class="t-text">A vivência de hoje foi mais uma vez, uma experiência única que superou as expectativas...</p></div>
        <div class="t-card man"><p class="t-name">Jean Camargo</p><p class="t-text">Hoje percebi que devemos cultivar amor próprio primordialmente para depois oferecer na relação...</p></div>
        <div class="t-card woman"><p class="t-name">Ivete</p><p class="t-text">Hoje percebi que valeu a pena o encontro de casal para entender um ao outro...</p></div>
        <div class="t-card man"><p class="t-name">Valdemar</p><p class="t-text">Valeu a pena porque senti a necessidade de buscar mais apoio quando o casal está com dores.</p></div>
        <div class="t-card woman"><p class="t-name">Roselei Teles</p><p class="t-text">Hoje percebi que um relacionamento saudável é baseado em confiança, em si mesma e no outro...</p></div>
        <div class="t-card woman"><p class="t-name">Claudete</p><p class="t-text">Valeu a pena pois percebi o quanto é importante a confiança e o compartilhamento de sonhos...</p></div>
      </div>
    </section>

    <!-- Inscrição -->
    <section id="inscricao">
      <h2>Garanta sua vaga</h2>
      <p>As vagas são limitadas. Clique no botão abaixo para iniciar sua inscrição.</p>
      <div style="display:flex;gap:12px;flex-wrap:wrap">
        <a class="card pink" href="#" title="Link do formulário/checkout" style="text-decoration:none;font-weight:700;text-align:center">Quero Participar</a>
        <a class="card blue" href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" target="_blank" rel="noopener" style="text-decoration:none;font-weight:700;text-align:center">Falar no WhatsApp</a>
      </div>
    </section>
  </main>

  <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="whatsapp-float" target="_blank" rel="noopener">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>

  <footer>
    © O Amor Presente — Vivência de Casais. Todos os direitos reservados.
  </footer>

</body>
</html>
