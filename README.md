
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>O Amor Presente — Vivência de Casais</title>
<meta name="description" content="Uma vivência pequena no tamanho e grande no sentido: um dia para reconectar, ouvir e escolher o amor de novo.">
<style>
  :root{
    --rose:#C9376E;        /* rosa da logo */
    --rose-soft:#FCE7F1;   /* rosa claro de apoio */
    --blue:#43A5FF;        /* azul da logo */
    --blue-soft:#E8F3FF;   /* azul claro de apoio */
    --ink:#1F2330;
    --soft:#667085;
    --line:#E9EEF5;
    --bg:#FFFFFF;
  }
  *{box-sizing:border-box}
  html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);
    font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
  img{max-width:100%;display:block}
  a{text-decoration:none}

  /* Página pequena */
  .wrap{max-width:880px;margin:0 auto;padding:22px}
  header{padding:20px 0 8px;background:#fff;border-bottom:1px solid var(--line)}
  .brand{display:flex;gap:14px;align-items:center;justify-content:center}
  .brand img{width:140px;height:auto}

  /* Cartão central pequeno */
  .card{margin:18px auto 16px;max-width:760px;background:#fff;border:1px solid var(--line);
    border-radius:18px;padding:22px 18px;box-shadow:0 8px 26px rgba(0,0,0,.06)}
  .tag{display:inline-block;background:linear-gradient(90deg,var(--rose-soft),var(--blue-soft));
    color:var(--rose);font-weight:700;font-size:12px;letter-spacing:.04em;text-transform:uppercase;
    padding:6px 10px;border-radius:999px;margin-bottom:6px}
  h1{font-size:clamp(26px,4.8vw,38px);margin:6px 0 8px;text-align:center}
  .lead{color:var(--soft);font-size:18px;text-align:center;max-width:640px;margin:0 auto}

  /* Frase que fala de amor */
  .poem{margin:14px auto 2px;max-width:640px;text-align:center;font-size:18px;color:#0f172a}
  .poem em{color:var(--rose)}
  .divider{height:8px;margin:16px auto 8px;max-width:220px;border-radius:999px;
    background:linear-gradient(90deg,var(--rose),var(--blue))}

  /* Blocos curtíssimos */
  .mini{display:grid;gap:12px;margin:12px auto 0;max-width:760px}
  .mini .item{background:linear-gradient(90deg,var(--blue-soft),#fff);border:1px solid var(--line);
    border-radius:14px;padding:12px 14px}
  .item strong{color:var(--rose)}
  .mentores{display:flex;gap:14px;align-items:center;justify-content:center;margin:12px auto 0}
  .mentores img{width:86px;height:86px;object-fit:cover;border-radius:12px;border:2px solid var(--line)}
  .mentores p{margin:0;color:var(--soft);font-size:14px}

  /* CTA compacto */
  .cta{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin:12px 0 4px}
  .btn{display:inline-block;padding:12px 16px;border-radius:12px;font-weight:800;box-shadow:0 6px 14px rgba(0,0,0,.06)}
  .primary{background:var(--rose);color:#fff}
  .ghost{background:#fff;border:2px solid var(--blue);color:var(--blue)}
  .primary:hover{filter:brightness(1.05)}
  .ghost:hover{background:var(--blue);color:#fff}

  /* Rodapé mini */
  footer{padding:18px 0 24px;text-align:center;color:#95A1B2;font-size:13px;border-top:1px solid var(--line)}
</style>
</head>
<body>

<div class="wrap">
  <header>
    <div class="brand">
      <img src="logo1.png" alt="Logo O Amor Presente">
    </div>
  </header>

  <main>
    <section class="card">
      <span class="tag">Vivência de Casais</span>
      <h1>O Amor Presente</h1>
      <p class="lead">Pequena no tamanho, grande no sentido: um encontro para <strong>ouvir</strong>, <strong>sentir</strong> e <strong>escolher o amor</strong> de novo.</p>

      <div class="poem">Amor é <em>presença</em>: olhar nos olhos, dar espaço à verdade,
        cuidar das raízes e lembrar — todos os dias — que o outro é a nossa casa.</div>
      <div class="divider" aria-hidden="true"></div>

      <div class="mini">
        <div class="item"><strong>Para quem?</strong> Casais que querem leveza, respeito e parceria — sem manual, sem julgamento.</div>
        <div class="item"><strong>O que acontece?</strong> Dinâmicas simples, conversa de coração aberto e um pacto de cuidado para a vida a dois.</div>
        <div class="item"><strong>Resultado:</strong> mais presença, mais diálogo, mais nós.</div>
      </div>

      <div class="mentores">
        <img src="evandro-alinne.jpg" alt="Evandro e Alinne">
        <p><strong>Evandro & Alinne</strong> — mentores da vivência. Facilitam com acolhimento, clareza e um olhar sistêmico sobre o vínculo.</p>
      </div>

      <div class="cta">
        <a href="https://wa.me/5549998110445?text=Quero%20saber%20mais%20sobre%20a%20Viv%C3%AAncia%20O%20Amor%20Presente" class="btn ghost" target="_blank" rel="noopener">Falar no WhatsApp</a>
        <a href="#inscricao" class="btn primary">Quero participar</a>
      </div>
    </section>

    <section id="inscricao" class="card" style="text-align:center">
      <p style="margin:0 0 8px;color:var(--soft)">Vagas limitadas • Horário: 08h às 17h • <em>Data & Local a confirmar</em></p>
      <a href="https://wa.me/5549998110445?text=Quero%20garantir%20minha%20vaga%20na%20Viv%C3%AAncia%20O%20Amor%20Presente" class="btn primary" target="_blank" rel="noopener">Garantir minha vaga</a>
    </section>
  </main>

  <footer>
    © O Amor Presente — Vivência de Casais
  </footer>
</div>

</body>
</html>
