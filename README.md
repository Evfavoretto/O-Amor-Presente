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

    /* BLOQUEIO AGRESSIVO — esconde header padrão e títulos de tema do GitHub Pages */
    body > header,
    .page-header,
    .site-header,
    header[role="banner"],
    .Header,
    #header,
    .project-name,
    .site-title,
    h1.project-name,
    h1.site-title{
      display:none !important;
      visibility:hidden !important;
      height:0 !important;
      margin:0 !important;
      padding:0 !important;
      border:0 !important;
      overflow:hidden !important;
    }

    /* FAIXA ROSA DE TOPO */
    .top-bar{
      background:var(--rose);
      color:#fff;
      text-align:center;
      padding:18px 10px;
      font-weight:900;
      font-size:clamp(20px,4.6vw,30px);
      letter-spacing:.04em;
      text-transform:uppercase;
    }

    /* HERO */
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

    /* FAQ — pergunta rosa / resposta azul */
    .faq{max-width:980px;margin:0 auto}
    .faq-item{
      margin:12px 0;
      border-radius:14px;
      overflow:hidden;
      box-shadow:0 6px 18px rgba(0,0,0,.06);
      border:1px solid var(--line);
    }
    .faq-q{
      width:100%;
      text-align:left;
      background:var(--rose);
      border:0;
      padding:16px 18px;
      font-size:18px;
      font-weight:900;
      color:#fff;
      cursor:pointer;
      display:flex; justify-content:space-between; align-items:center;
    }
    .faq-q .mark{flex:0 0 auto; font-weight:900; color:#fff}
    .faq-q:focus{outline:3px solid var(--blue-2)}
    .faq-a{
      max-height:0;
      overflow:hidden;
      transition:max-height .28s ease;
      background:var(--blue);
      color:#fff;
      border-top:1px solid var(--line);
    }
    .faq-a-inner{padding:16px 18px; font-size:16px; line-height:1.55}
    .faq-item.open .faq-a{max-height:360px}
    .faq-item.open .faq-q .mark{opacity:.9}

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
    @media (max-width:640px){
      .whats-float{top:auto; bottom:18px; right:18px; transform:none;}
    }
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
            <p>Mais que um encontro: um dia imersivo para casais mergulharem em experiências que abrem espaço para diálogo, afeto, perdão e sonho compartilhado. Aqui, vocês vão se olhar de novo, se ouvir de verdade e reencontrar o amor como escolha diária.</p>
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
          <p><strong>Evandro & Alinne</strong> — mentores com olhar sistêmico e acolhedor para fortalecer a parceria: desenvolvimento humano, constelação familiar e empresarial, e inteligência emocional.</p>
        </div>

        <!-- CTA primária -->
        <div class="cta">
          <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente"
             class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>

          <!-- Fora do WhatsApp: vai para o Google Forms (nova guia) -->
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSc7wsV5YQcTsjH9x3CSAVRu13jba3_sSbD39dFqQgxWprBqXQ/viewform"
             class="btn primary" target="_blank" rel="noopener">Quero participar</a>
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
        <div class="t-card woman"><p class="t-name">Grasiela Nardino</p><p>Hoje percebi que devemos olhar mais para nós como casal, apoiar e ouvir a opinião do outro e sempre levar em consideração ambas as colocações. Em sintonia podemos crescer e evoluir muito mais.</p></div>
        <div class="t-card man"><p class="t-name">Mateus Battistela</p><p>Hoje valeu a pena porque aprendi um pouco mais sobre nosso relacionamento, as linguagens do amor e a importância de saber ouvir e se apoiar.</p></div>
        <div class="t-card woman"><p class="t-name">Alini De Paris</p><p>A comunicação clara e expressiva, respeitando o tempo e a individualidade do outro, cria um ambiente mais seguro e acolhedor, fortalecendo nossa conexão emocional.</p></div>
        <div class="t-card man"><p class="t-name">Marcelo Pissaia Novo</p><p>Devemos olhar para quem está ao nosso lado com amor e respeito, nos apoiar nos momentos difíceis e nunca largar a mão.</p></div>
        <div class="t-card woman"><p class="t-name">Joice</p><p>Uma experiência única que superou as expectativas. Precisamos cuidar do nosso casamento para vivermos de maneira leve e feliz.</p></div>
        <div class="t-card man"><p class="t-name">Jean Camargo</p><p>Percebi que precisamos cultivar amor próprio para depois oferecer na relação, em sintonia na comunicação e escutando com amor — cultivando boas raízes.</p></div>
        <div class="t-card woman"><p class="t-name">Ivete</p><p>Valeu a pena o encontro de casal para entender um ao outro, apoiar sempre, tirar as dores e cuidar das nossas raízes.</p></div>
        <div class="t-card man"><p class="t-name">Valdemar</p><p>Senti a necessidade de buscar mais apoio quando o casal está com dores.</p></div>
        <div class="t-card woman"><p class="t-name">Roselei Teles</p><p>Um relacionamento saudável é baseado em confiança, em si mesma e no outro; compreender as dores e respeitar o momento de cada um.</p></div>
        <div class="t-card woman"><p class="t-name">Claudete</p><p>Importante a confiança e o compartilhamento de sonhos e projetos. Condução e responsabilidade caminham juntas.</p></div>
      </div>
    </div>
  </section>

  <!-- É PARA VOCÊ / NÃO É PARA VOCÊ -->
  <section id="para-quem">
    <div class="wrap">
      <h2 class="section-title">É para você se... / Não é para você se...</h2>

      <div class="fit-grid">
        <!-- É para você -->
        <div class="fit-card fit-yes">
          <h3 class="fit-title">É para você se...</h3>
          <ul class="fit-list">
            <li><span class="icon ok">✓</span><span>Vocês querem <strong>reconectar</strong> e fortalecer o diálogo com leveza e respeito.</span></li>
            <li><span class="icon ok">✓</span><span>Topam olhar para <strong>padrões da relação</strong> e assumir corresponsabilidade.</span></li>
            <li><span class="icon ok">✓</span><span>Estão dispostos a <strong>praticar linguagens do amor</strong> no cotidiano.</span></li>
            <li><span class="icon ok">✓</span><span>Buscam um <strong>espaço seguro</strong>, com condução profissional e acolhedora.</span></li>
            <li><span class="icon ok">✓</span><span>Podem dedicar um <strong>dia inteiro</strong> de presença para a relação.</span></li>
          </ul>
        </div>

        <!-- Não é para você -->
        <div class="fit-card fit-no">
          <h3 class="fit-title">Não é para você se...</h3>
          <ul class="fit-list">
            <li><span class="icon no">×</span><span>Procura <strong>terapia individual/psiquiátrica de urgência</strong> ou atendimento clínico.</span></li>
            <li><span class="icon no">×</span><span>Espera <strong>solução mágica</strong> sem participação ativa.</span></li>
            <li><span class="icon no">×</span><span>Quer “<strong>vencer discussões</strong>” ou expor o parceiro(a) no grupo.</span></li>
            <li><span class="icon no">×</span><span>Há <strong>situação de violência</strong> no relacionamento (encaminhamos à rede de proteção adequada).</span></li>
            <li><span class="icon no">×</span><span>Não é possível estarem <strong>presencialmente juntos</strong> no dia da vivência.</span></li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ (pergunta rosa, resposta azul) -->
  <section id="faq">
    <div class="wrap">
      <h2 class="section-title">Perguntas Frequentes</h2>
      <div class="faq">

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>Para quem é a vivência?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Para casais em qualquer fase (namoro, noivado, casamento ou restauração) que desejam reconectar, comunicar melhor e fortalecer o vínculo com leveza e presença.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>Precisa expor a vida do casal no grupo?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Não. O encontro é conduzido com acolhimento e segurança. Há momentos individuais e em dupla, e você escolhe o que deseja compartilhar.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>O que acontece durante o dia?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Dinâmicas em casal, reflexões guiadas, exercícios práticos de comunicação e experiências inspiradas em princípios sistêmicos para ressignificar histórias e pactos.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>Há pré-requisito para participar?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Apenas a presença dos dois e abertura para a experiência. Não é necessário conhecimento prévio em constelação ou outras abordagens.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>O investimento é por pessoa ou por casal?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              O valor informado na página é por casal. Os lotes variam conforme a disponibilidade de vagas.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>Qual é o horário e a duração?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Um dia inteiro de imersão, das 08h00 às 17h00. Data e local serão confirmados diretamente no WhatsApp após o cadastro.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>O que levar no dia?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Roupas confortáveis, água, e um caderno para anotações. O essencial é a disponibilidade para viver a experiência em presença.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-q" aria-expanded="false">
            <span>Como faço para garantir a vaga?</span>
            <span class="mark">+</span>
          </button>
          <div class="faq-a" aria-hidden="true">
            <div class="faq-a-inner">
              Clique em “Quero participar” ou fale conosco no WhatsApp. Enviaremos o link de inscrição e as instruções de pagamento conforme o lote vigente.
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- INSCRIÇÃO (fora do WhatsApp: Google Forms em nova guia) -->
  <section id="inscricao" style="padding:40px 20px">
    <div class="wrap" style="text-align:center">
      <p style="margin:0 0 12px;color:var(--soft)">Vagas limitadas • 08h às 17h • <em>Data & Local a confirmar</em></p>

      <a href="https://docs.google.com/forms/d/e/1FAIpQLSc7wsV5YQcTsjH9x3CSAVRu13jba3_sSbD39dFqQgxWprBqXQ/viewform"
         class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>

      <div style="margin-top:10px">
        <a href="https://wa.me/5549998110445?text=Enviei%20o%20formul%C3%A1rio%20da%20Viv%C3%AAncia%20O%20Amor%20Presente"
           class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
      </div>
    </div>
  </section>

  <!-- CTA FINAL (fora do WhatsApp: Forms em nova guia) -->
  <section style="padding:32px 20px">
    <div class="wrap">
      <div class="footer-cta">
        <div>
          <div style="font-weight:800;color:var(--rose);letter-spacing:.06em;text-transform:uppercase;font-size:12px">Pronto para reconectar?</div>
          <h3 style="margin:6px 0 0;font-size:22px;color:var(--ink)">Um dia para lembrar, sentir e escolher novamente o amor.</h3>
        </div>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSc7wsV5YQcTsjH9x3CSAVRu13jba3_sSbD39dFqQgxWprBqXQ/viewform"
           class="btn primary" target="_blank" rel="noopener">Inscrever-se agora</a>
      </div>
    </div>
  </section>

  <!-- RODAPÉ ROSA -->
  <footer>
    © O Amor Presente — Vivência de Casais. Todos os direitos reservados.
  </footer>

  <!-- BOTÃO FLUTUANTE WHATSAPP -->
  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" target="_blank" rel="noopener" aria-label="Falar no WhatsApp">
    <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <!-- JS do FAQ + REMOÇÃO AGRESSIVA DO HEADER DO GITHUB -->
  <script>
    (function(){
      // FAQ: abre um por vez
      const items = document.querySelectorAll('.faq-item');
      items.forEach((item) => {
        const btn = item.querySelector('.faq-q');
        const panel = item.querySelector('.faq-a');
        btn.addEventListener('click', () => {
          items.forEach(i => {
            if(i !== item){
              i.classList.remove('open');
              const b = i.querySelector('.faq-q');
              const p = i.querySelector('.faq-a');
              b && b.setAttribute('aria-expanded','false');
              p && p.setAttribute('aria-hidden','true');
            }
          });
          const isOpen = item.classList.toggle('open');
          btn.setAttribute('aria-expanded', isOpen ? 'true' : 'false');
          panel.setAttribute('aria-hidden', isOpen ? 'false' : 'true');
        });
      });

      // REMOÇÃO AGRESSIVA de header/título do GitHub Pages
      const killSelectors = [
        'body > header',
        '.page-header',
        '.site-header',
        'header[role="banner"]',
        '.Header',
        '#header',
        '.project-name',
        '.site-title',
        'h1.project-name',
        'h1.site-title'
      ];
      killSelectors.forEach(sel => {
        document.querySelectorAll(sel).forEach(el => el && el.remove());
      });

      // Se ainda sobrar um H1 solto no topo antes da nossa faixa, remove
      const bodyChildren = Array.from(document.body.children);
      for(let i=0;i<bodyChildren.length;i++){
        const el = bodyChildren[i];
        if(el.classList && el.classList.contains('top-bar')) break;
        if(el.tagName === 'H1') { el.remove(); break; }
      }

      // Também remove H1 com texto igual ao nome do repo (por segurança)
      document.querySelectorAll('h1').forEach(h=>{
        const t = (h.textContent || '').trim().toLowerCase();
        if(t === 'o amor presente' || t === 'amor presente'){
          h.remove();
        }
      });
    })();
  </script>
</body>
</html>
