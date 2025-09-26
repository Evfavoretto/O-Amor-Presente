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
      padding:24px;
      color:#fff;
    }

    header img.logo {max-width:200px;margin-bottom:12px}
    header .badge {font-size:18px;font-weight:700;text-transform:uppercase;letter-spacing:.05em}

    section {padding:48px 20px;max-width:1100px;margin:0 auto}

    h2 {
      font-size:28px;
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
      padding:22px;
      box-shadow:0 8px 24px rgba(0,0,0,.05);
    }
    .pink {background:var(--rose-light)}
    .blue {background:var(--blue-light)}

    ul{margin:0;padding-left:20px;color:var(--soft)}
    li{margin:8px 0;font-size:18px}
    .list-check li{list-style:none;position:relative;padding-left:28px}
    .list-check li:before{content:"✓";color:var(--success);font-weight:800;position:absolute;left:0;top:0}

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
    <img src="logo1.png" alt="Logo O Amor Presente" class="logo">
    <div class="badge">Vivência de Casais</div>
  </header>

  <main>
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
  </main>

  <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="whatsapp-float" target="_blank" rel="noopener">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>

  <footer>
    © O Amor Presente — Vivência de Casais. Todos os direitos reservados.
  </footer>

</body>
</html>
