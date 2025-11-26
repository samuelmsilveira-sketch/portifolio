# portifolio
MINHA ATIVIDADE
!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfólio • Samuel</title>
  <meta name="description" content="Portfólio de Samuel — desenvolvedor web, projetos, habilidades e contato." />
  <style>
    :root{
      --bg:#1a0000; --card:#230202; --muted:#e4b4b4; --accent:#ff3b3b; --glass: rgba(255,255,255,0.03);
      --maxw:1100px;
      color-scheme: dark;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--bg),#150000);color:#ffeaea;line-height:1.5}
    .container{max-width:var(--maxw);margin:36px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#ff6b6b);display:flex;align-items:center;justify-content:center;font-weight:700;color:#330000}
    nav a{color:var(--muted);text-decoration:none;margin-left:14px}
    nav a:hover{color:var(--accent)}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:28px;margin-top:28px;align-items:center}
    .card{background:var(--card);padding:20px;border-radius:14px;box-shadow:0 6px 20px rgba(0,0,0,0.6);backdrop-filter:blur(6px)}
    h1{margin:0 0 6px 0;font-size:clamp(20px,3vw,32px)}
    p.lead{color:var(--muted);margin:0 0 14px}
    .cta{display:flex;gap:10px;margin-top:12px}
    .btn{padding:10px 14px;border-radius:10px;border:none;cursor:pointer;font-weight:600}
    .btn-primary{background:linear-gradient(90deg,var(--accent),#ff6b6b);color:#330000}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}
    .btn:hover{opacity:0.85;transition:opacity .2s}
    button{font-family:inherit}

    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:18px}
    .project{padding:14px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);border:1px solid rgba(255,255,255,0.03)}
    .project h3{margin:0 0 6px;font-size:16px}
    .project p{color:var(--muted);margin:0 0 10px;font-size:14px}
    .tags{display:flex;flex-wrap:wrap;gap:8px}
    .tag{font-size:12px;padding:6px 8px;border-radius:999px;background:var(--glass);color:var(--muted)}

    .skills{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .skill{padding:10px 12px;border-radius:10px;background:rgba(255,255,255,0.02);color:var(--muted);font-weight:600}

    input,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:#150000;color:inherit;font-family:inherit}
    input:focus,textarea:focus{outline:none;border-color:rgba(255,255,255,0.1)}
    textarea{min-height:120px;resize:vertical}
    input,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:#150000;color:inherit}
    textarea{min-height:120px;resize:vertical}

    footer{margin-top:34px;text-align:center;color:var(--muted);font-size:13px}

    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      .contact-grid{grid-template-columns:1fr}
    }

    .project:hover{transform:translateY(-6px);transition:transform .18s}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">S</div>
        <div>
          <div style="font-weight:700">Samuel</div>
          <div style="font-size:13px;color:var(--muted)">Desenvolvedor Web</div>
        </div>
      </div>
      <nav>
        <a href="#sobre">Sobre</a>
        <a href="#projetos">Projetos</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#contato">Contato</a>
    <section id="sobre" class="hero">
      <div class="card">
        <h1>Olá — eu sou <span style="color:var(--accent)">Samuel</span></h1>
    <section class="hero">
      <div class="card">
        <h1>Olá — eu sou <span style="color:var(--accent)">Samuel</span></h1>
        <p class="lead">Sou uma pessoa calma e tranquila, gosto de criar projetos com foco em simplicidade e boas experiências.</p>
        <div class="cta">
          <a class="btn btn-primary" href="#projetos">Ver Projetos</a>
          <a class="btn btn-ghost" href="#contato">Entrar em Contato</a>
        </div>
      </div>

      <aside class="card">
        <h3 style="margin-top:0">Contatos</h3>
        <p style="margin:6px 0;color:var(--muted)"><strong>Email:</strong> samuel@gmail.com</p>
        <p style="margin:6px 0;color:var(--muted)"><strong>Local:</strong> Brasil</p>
      </aside>
    </section>

    <section id="projetos" style="margin-top:24px">
      <h2 style="margin:0 0 8px 0">Projetos</h2>
      <div class="projects">
        <article class="project">
          <h3>Projeto 1 — Site Institucional</h3>
          <p>Site institucional simples com design moderno e responsivo.</p>
          <div class="tags">
            <span class="tag">HTML</span><span class="tag">CSS</span>
          </div>
        </article>

        <article class="project">
          <h3>Projeto 2 — App de Tarefas</h3>
          <p>Aplicativo de tarefas com salvamento local e filtro de prioridade.</p>
          <div class="tags">
            <span class="tag">JavaScript</span>
          </div>
        </article>
      </div>
    </section>

    <section id="habilidades" style="margin-top:22px">
      <h2 style="margin:0 0 8px 0">Habilidades</h2>
      <div class="card">
        <div class="skills">
          <div class="skill">HTML & CSS</div>
          <div class="skill">JavaScript</div>
          <div class="skill">Design Responsivo</div>
        </div>
      </div>
    </section>

    <section id="contato" style="margin-top:22px">
      <h2 style="margin:0 0 8px 0">Contato</h2>
      <form class="card" action="#" onsubmit="alert('Formulário de exemplo — substituir backend.');return false;">
        <label for="nome">Nome</label>
        <input id="nome" placeholder="Seu nome" required />

        <label for="email">Email</label>
        <input id="email" type="email" placeholder="seu@email.com" required />

        <label for="mensagem">Mensagem</label>
        <textarea id="mensagem" placeholder="Escreva uma mensagem..." required></textarea>

        <div style="margin-top:12px;display:flex;gap:8px;justify-content:flex-end">
          <button class="btn btn-ghost" type="reset">Limpar</button>
          <button class="btn btn-primary" type="submit">Enviar</button>
        </div>
      </form>
    </section>

    <footer>
      <p>Feito por Samuel</p>
    </footer>
  </div>

  <script>
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const href=a.getAttribute('href');
        if(href.length>1){
          e.preventDefault();
          const el=document.querySelector(href);
          if(el) el.scrollIntoView({behavior:'smooth',block:'start'});
        }
      })
    });
  </script>
</body>
</html>
