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

    /* FAIXA ROSA FIXA */
    .top-bar{
      position:fixed;
      top:0;left:0;right:0;
      background:var(--rose);
      color:#fff;
      text-align:center;
      padding:18px 10px;
      font-weight:900;
      font-size:clamp(20px,4.6vw,30px);
      letter-spacing:.04em;
      text-transform:uppercase;
      z-index:9999;
    }
    body{padding-top:70px} /* empurra o conteúdo para baixo da faixa */

    /* HERO */
    .hero{padding:28px 20px 10px;background:#fff}
    .wrap{max-width:1100px;margin:0 auto}
    .hero-card{
      background:#fff;border:1px solid var(--line);border-radius:22px;
      padding:28px 28px 34px;margin:0 auto;max-width:980px;
      box-shadow:0 14px 34px rgba(0,0,0,.06);text-align:center
    }
    .logo{max-height:170px;width:auto;margin:6px auto 10px}
    @media(max-width:640px){
      .logo{max-height:110px} /* logo menor no celular */
    }
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

    /* CARDS */
    .card{background:#fff;border:1px solid var(--line);border-radius:18px;padding:24px;box-shadow:0 10px 28px rgba(31,35,48,.05)}
    .pink{background:var(--rose-2)}
    .blue{background:var(--blue-2)}

    /* INSTRUTORES */
    .mentores{text-align:center}
    .mentores img{max-width:380px;border-radius:16px;box-shadow:0 10px 26px rgba(0,0,0,.08);margin:12px auto 6px}
    @media(max-width:640px){
      .mentores img{max-width:250px}
    }

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

    /* É PARA VOCÊ */
    .fit-grid{display:grid;gap:22px}
    @media(min-width:860px){.fit-grid{grid-template-columns:1fr 1fr}}
    .fit-card{border:1px solid var(--line);border-radius:18px;padding:22px;box-shadow:0 10px 26px rgba(0,0,0,.05)}
    .fit-yes{background:#ECFDF5}
    .fit-no{background:#FFE4EA}

    /* FAQ */
    .faq{max-width:980px;margin:0 auto}
    .faq-item{margin:12px 0;border-radius:14px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.06);border:1px solid var(--line)}
    .faq-q{width:100%;text-align:left;background:var(--rose);border:0;padding:16px 18px;font-size:18px;font-weight:900;color:#fff;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .faq-a{max-height:0;overflow:hidden;transition:max-height .28s ease;background:var(--blue);color:#fff}
    .faq-a-inner{padding:16px 18px;font-size:16px;line-height:1.55}
    .faq-item.open .faq-a{max-height:360px}

    /* FOOTER */
    .footer-cta{background:var(--blue-2);border:1px solid #dbeafe;border-radius:16px;padding:26px;display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between}
    footer{padding:28px 0;background:var(--rose);color:#fff;font-size:14px;text-align:center}

    /* WHATSAPP */
    .whats-float{position:fixed;right:40px;top:50%;transform:translateY(-50%);z-index:1000;width:60px;height:60px;border-radius:50%;background:#25D366;box-shadow:0 12px 28px rgba(0,0,0,.18);display:flex;align-items:center;justify-content:center}
    .whats-float svg{width:30px;height:30px;fill:#fff}
    @media(max-width:640px){
      .whats-float{top:auto;bottom:18px;right:18px;transform:none;}
    }
  </style>
</head>
<body>

  <div class="top-bar">VIVÊNCIA DE CASAIS</div>

  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <img src="logo.png" alt="Logo O Amor Presente" class="logo">
        <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”.</strong></p>
        <div class="divider"></div>

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

        <div class="mentores">
          <h2 class="section-title">Instrutores</h2>
          <img src="evandro-alinne.jpg" alt="Evandro & Alinne — mentores da vivência">
          <p><strong>Evandro & Alinne</strong> — mentores com olhar sistêmico e acolhedor para fortalecer a parceria: desenvolvimento humano, constelação familiar e empresarial, e inteligência emocional.</p>
        </div>

        <div class="cta">
          <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="btn ghost" target="_blank">Falar no WhatsApp</a>
          <a href="#inscricao" class="btn primary">Quero participar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- (mantém as seções de investimento, depoimentos, é para você, FAQ, inscrição, CTA final e rodapé iguais ao código anterior) -->

  <a class="whats-float" href="https://wa.me/5549998110445?text=Oi%20Evandro!%20Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" target="_blank">
    <svg viewBox="0 0 24 24"><path d="M20.5 3.5A10 10 0 0 0 3.2 17.7L2 22l4.4-1.2A10 10 0 1 0 20.5 3.5Zm-8.4 2.2c4.1 0 7.4 3.3 7.4 7.4a7.4 7.4 0 0 1-10.1 6.8l-.3-.1-2.6.7.7-2.5-.1-.3a7.4 7.4 0 0 1 5-11.9Zm4.2 9.8c-.2.6-1.1 1-1.5 1.1-.4.1-.9.1-1.5 0s-1.5-.5-2.6-1.1c-1-.6-1.8-1.6-2.1-2.1-.3-.5-.5-1.3-.1-1.9.2-.3.5-.8.8-.8h.6c.1 0 .4-.1.6.5.2.6.8 2 .9 2.2.1.2.1.4 0 .6s-.2.4-.4.6c-.2.2-.4.4-.2.7.2.3.9 1.4 2.1 2 .9.5 1.6.6 1.9.4.3-.2.4-.5.6-.8.2-.3.5-.4.8-.3l1.9.9c.3.1.5.3.6.5Z"/></svg>
  </a>

  <script>
    (function(){
      const items = document.querySelectorAll('.faq-item');
      items.forEach((item) => {
        const btn = item.querySelector('.faq-q');
        const panel = item.querySelector('.faq-a');
        btn.addEventListener('click', () => {
          items.forEach(i => {
            if(i !== item){
              i.classList.remove('open');
            }
          });
          item.classList.toggle('open');
        });
      });
    })();
  </script>
</body>
</html>
