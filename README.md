<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vivência de Casais – O Amor Presente</title>
  <meta name="description" content="Vivência de Casais O Amor Presente — um dia inteiro para reconectar, comunicar, ressignificar e fortalecer o compromisso consciente." />
  <style>
    :root{
      --rose:#C9376E;
      --rose-2:#FCE9F0;
      --blue:#4DA6FF;
      --blue-2:#E6F3FF;
      --ink:#1f2330;
      --soft:#6b7280;
      --bg:#fff;
      --success:#10B981;
    }

    /* Zera margens e garante que nada fique antes do header */
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Arial}
    *{box-sizing:border-box}
    a{color:var(--rose);text-decoration:none}

    /* ----- HERO (faixa rosa fixa colada no topo) ----- */
    header{
      position:fixed;        /* cola no topo e cobre o título azul do GitHub */
      top:0; left:0; right:0;
      z-index:999;
      background:linear-gradient(135deg,var(--rose) 0%, #b43c7b 40%, #8c2aa0 70%);
      color:#fff;
      text-align:center;
      padding:140px 20px 80px;  /* altura generosa para cobrir qualquer coisa */
    }
    header .wrap{max-width:1100px;margin:0 auto}
    header img.logo{
      max-height:170px;      /* mais retangular, sem distorcer */
      width:auto;
      display:block;
      margin:0 auto 16px;
    }
    .badge{
      display:inline-block;
      background:rgba(255,255,255,.15);
      border:1px solid rgba(255,255,255,.25);
      padding:8px 14px;
      border-radius:999px;
      font-weight:700;
      letter-spacing:.06em;
      text-transform:uppercase;
    }
    .subtitle{
      max-width:820px;
      margin:14px auto 0;
      font-size:clamp(16px,2.6vw,20px);
      opacity:.95;
    }
    .cta-wrap{display:flex;gap:12px;flex-wrap:wrap;justify-content:center;margin-top:26px}
    .btn{display:inline-block;padding:12px 18px;border-radius:12px;font-weight:700;box-shadow:0 6px 14px rgba(0,0,0,.12)}
    .btn-primary{background:#fff;color:var(--rose)}
    .btn-outline{border:2px solid #fff;color:#fff}

    /* empurra o conteúdo para baixo do header fixo */
    main{padding-top:320px}

    /* ----- LAYOUT BASE ----- */
    .container{max-width:1100px;margin:0 auto;padding:0 20px}
    section{padding:56px 0;border-bottom:1px solid #f1f5f9}
    .grid{display:grid;gap:22px}
    .two{grid-template-columns:1fr}
    @media(min-width:860px){.two{grid-template-columns:1fr 1fr}}

    h2{
      font-size:clamp(26px,3.8vw,38px);
      margin:0 0 14px;
      background:linear-gradient(90deg,var(--rose),var(--blue));
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent;
      font-weight:800;
    }
    p{margin:10px 0 0;font-size:18px;color:var(--soft)}

    .card{
      background:#fff;border:1px solid #e5e7eb;border-radius:16px;padding:24px;
      box-shadow:0 8px 24px rgba(0,0,0,.06);
    }
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}

    ul{margin:8px 0 0 18px;color:var(--soft);font-size:18px}
    li{margin:8px 0}
    .list-check li{list-style:none;padding-left:28px;position:relative}
    .list-check li:before{content:"✓";position:absolute;left:0;top:0;color:var(--success);font-weight:800}

    /* ----- INSTRUTORES ----- */
    .mentores{text-align:center}
    .mentores img{max-width:360px;border-radius:16px;box-shadow:0 10px 26px rgba(0,0,0,.08);margin:10px auto 14px;display:block}

    /* ----- PREÇOS ----- */
    .pricing{display:grid;gap:16px}
    @media(min-width:860px){.pricing{grid-template-columns:repeat(3,1fr)}}
    .price-card{text-align:center;border:1px solid #e5e7eb;border-radius:16px;padding:22px;background:#fff}
    .price{font-size:34px;font-weight:900;color:var(--rose);margin:8px 0}
    .pill{display:inline-block;background:var(--blue-2);color:var(--blue);padding:4px 10px;border-radius:999px;font-weight:700;font-size:12px}

    /* ----- DEPOIMENTOS ----- */
    .testimonials{display:grid;gap:18px}
    @media(min-width:860px){.testimonials{grid-template-columns:1fr 1fr}}
    .t-card{border:1px solid #e5e7eb;border-radius:16px;padding:18px;box-shadow:0 8px 24px rgba(0,0,0,.05)}
    .t-name{font-weight:800;margin:0 0 8px}
    .woman{background:var(--rose-2)}
    .man{background:var(--blue-2)}

    /* ----- RODAPÉ ----- */
    .footer-cta{background:var(--blue-2);border:1px solid #dbeafe;border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between}
    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    /* ----- WHATSAPP FLUTUANTE ----- */
    .whatsapp-float{
      position:fixed;
      right:40px;            /* “mais para a esquerda” em relação à borda */
      top:50%;
      transform:translateY(-50%);
      width:60px;height:60px;border-radius:50%;
      background:#25D366;display:flex;align-items:center;justify-content:center;
      box-shadow:0 6px 18px rgba(0,0,0,.2);z-index:1000;
    }
    .whatsapp-float img{width:32px;height:32px}
  </style>
</head>
<body>

  <!-- HERO -->
  <header>
    <div class="wrap">
      <img src="logo.png" alt="Logo O Amor Presente" class="logo">
      <div class="badge">Vivência de Casais</div>
      <p class="subtitle"><strong>“Reconectar: A Linguagem do Amor em Movimento”</strong> — um dia para olhar, ouvir e resolver o vínculo com presença.</p>
      <div class="cta-wrap">
        <a href="#inscricao" class="btn btn-primary">Quero participar</a>
        <a href="#como-sera" class="btn btn-outline">Como será o dia?</a>
      </div>
    </div>
  </header>

  <main>
    <div class="container">
      <!-- O que é + Resultados -->
      <section id="como-sera">
        <div class="grid two">
          <div class="card pink">
            <h2>O que é a vivência?</h2>
            <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado. Aqui, vocês vão se olhar de novo, se ouvir de verdade e reencontrar o amor como escolha diária.</p>
          </div>
          <div class="card blue">
            <h2>Resultados</h2>
            <ul class="list-check">
              <li><strong>Reconexão emocional</strong> e leveza;</li>
              <li><strong>Comunicação respeitosa e clara</strong>;</li>
              <li><strong>Ressignificação de feridas</strong> e aprendizados;</li>
              <li><strong>Compromisso consciente</strong> no dia a dia.</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Instrutores -->
      <section id="instrutores" class="mentores">
        <h2>Instrutores</h2>
        <img src="evandro-alinne.jpg" alt="Evandro & Alinne — mentores da vivência" />
        <p><strong>Evandro & Alinne</strong> facilitam a vivência com olhar sistêmico e acolhedor, integrando desenvolvimento humano, constelação familiar e empresarial, e inteligência emocional para fortalecer a parceria.</p>
      </section>

      <!-- Investimento -->
      <section id="precos">
        <h2>Investimento (por casal)</h2>
        <div class="pricing">
          <div class="price-card">
            <div class="pill">1º Lote</div>
            <div class="price">R$ 620,00</div>
            <p class="soft">Vagas limitadas</p>
          </div>
          <div class="price-card">
            <div class="pill">2º Lote</div>
            <div class="price">R$ 800,00</div>
            <p class="soft">Sujeito à disponibilidade</p>
          </div>
          <div class="price-card">
            <div class="pill">3º Lote</div>
            <div class="price">R$ 998,00</div>
            <p class="soft">Últimas vagas</p>
          </div>
        </div>
      </section>

      <!-- Depoimentos (mulher/ homem alternando) -->
      <section id="depoimentos">
        <h2>Depoimentos</h2>
        <div class="testimonials">
          <div class="t-card woman">
            <p class="t-name">Grasiela Nardino</p>
            <p>Hoje percebi que devemos olhar mais para nós como casal, apoiar e ouvir a opinião do outro e sempre levar em consideração ambas as colocações, em sintonia podemos crescer e evoluir muito mais.</p>
          </div>
          <div class="t-card man">
            <p class="t-name">Mateus Battistela</p>
            <p>Hoje valeu a pena porque aprendi um pouco mais sobre nosso relacionamento, as linguagens do amor e a importância de saber ouvir e se apoiar.</p>
          </div>
          <div class="t-card woman">
            <p class="t-name">Alini De Paris</p>
            <p>Hoje valeu a pena porque a comunicação clara e expressiva em um relacionamento é muito importante, bem como saber respeitar o tempo e a individualidade do outro. Através da compreensão criamos um ambiente mais seguro e acolhedor, fortalecendo nossa conexão emocional.</p>
          </div>
          <div class="t-card man">
            <p class="t-name">Marcelo Pissaia Novo</p>
            <p>Hoje percebi que devemos olhar para a pessoa que está ao nosso lado com amor e respeito, devemos nos apoiar nos momentos difíceis e nunca largar a mão.</p>
          </div>
          <div class="t-card woman">
            <p class="t-name">Joice</p>
            <p>A vivência de hoje foi, mais uma vez, uma experiência única que superou as expectativas. Precisamos cuidar do nosso casamento para que possamos viver de maneira leve e feliz.</p>
          </div>
          <div class="t-card man">
            <p class="t-name">Jean Camargo</p>
            <p>Hoje percebi que devemos cultivar amor próprio primordialmente para, na sequência, ter para oferecer na relação; estar em sintonia na comunicação, escutando com amor e cultivando boas raízes.</p>
          </div>
          <div class="t-card woman">
            <p class="t-name">Ivete</p>
            <p>Hoje percebi que valeu a pena o encontro de casal para entender um ao outro, apoiar sempre, tirar as dores e cuidar das nossas raízes.</p>
          </div>
          <div class="t-card man">
            <p class="t-name">Valdemar</p>
            <p>Valeu a pena porque senti a necessidade de buscar mais apoio quando o casal está com dores.</p>
          </div>
          <div class="t-card woman">
            <p class="t-name">Roselei Teles</p>
            <p>Hoje percebi que um relacionamento saudável é baseado, em primeiro lugar, em confiança — em si mesma e no outro —, compreender as dores um do outro e respeitar o momento de cada um.</p>
          </div>
          <div class="t-card woman">
            <p class="t-name">Claudete</p>
            <p>Percebi o quanto é importante a confiança e o compartilhamento de sonhos e projetos com o parceiro. A dinâmica da condução mostrou o valor de confiar quando somos conduzidos e a responsabilidade quando estamos conduzindo.</p>
          </div>
        </div>
      </section>

      <!-- Inscrição -->
      <section id="inscricao" style="text-align:center">
        <h2>Garanta sua vaga</h2>
        <p>As vagas são limitadas. Clique no botão abaixo para iniciar sua inscrição.</p>
        <div class="cta-wrap" style="justify-content:center">
          <a class="btn btn-primary" href="#" title="Link do formulário/checkout">Quero participar</a>
          <a class="btn" style="background:var(--blue-2);color:var(--blue)"
             href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente"
             target="_blank" rel="noopener">Falar no WhatsApp</a>
        </div>
      </section>

      <!-- CTA final -->
      <section>
        <div class="footer-cta">
          <div>
            <div style="font-weight:800;color:var(--rose);letter-spacing:.06em;text-transform:uppercase;font-size:12px">Pronto para reconectar?</div>
            <h3 style="margin:6px 0 0;font-size:22px;color:var(--ink)">Um dia para lembrar, sentir e escolher novamente o amor.</h3>
          </div>
          <a href="#inscricao" class="btn btn-primary">Inscrever-se agora</a>
        </div>
      </section>
    </div>
  </main>

  <footer>
    © O Amor Presente — Vivência de Casais. Todos os direitos reservados.
  </footer>

  <!-- Botão flutuante WhatsApp (meio da página, mais para dentro) -->
  <a class="whatsapp-float" target="_blank" rel="noopener"
     href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  </a>
</body>
</html>
