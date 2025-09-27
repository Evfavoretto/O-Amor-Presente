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

    /* HERO COM CARTÃO BRANCO */
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

    /* (mantém os outros estilos do teu código como preços, FAQ etc) */
  </style>
</head>
<body>

  <!-- FAIXA ROSA -->
  <div class="top-bar">VIVÊNCIA DE CASAIS</div>

  <!-- HERO -->
  <div class="hero">
    <div class="wrap">
      <div class="hero-card">
        <img src="logo.png" alt="Logo O Amor Presente" class="logo">
        <p class="lead"><strong>“Reconectar: A Linguagem do Amor em Movimento”.</strong></p>
        <div class="divider"></div>
        <!-- resto do conteúdo -->
      </div>
    </div>
  </div>

</body>
</html>
