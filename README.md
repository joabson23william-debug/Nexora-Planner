
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#111827">
<meta name="description" content="Materiais digitais práticos para organizar sua rotina, suas finanças e seu trabalho.">
<title>Nexora — Ideias que viram resultados</title>
<style>
:root {
  --bg: #111827;
  --card: #1f2937;
  --green: #a3e635;
  --white: #f9fafb;
  --muted: #cbd5e1;
}
* { box-sizing: border-box; }
body {
  margin: 0;
  background: var(--bg);
  color: var(--white);
  font-family: Arial, sans-serif;
  line-height: 1.6;
}
header, footer {
  padding: 22px 7%;
  border-bottom: 1px solid #374151;
}
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
}
.logo { font-size: 25px; font-weight: 800; }
.logo span { color: var(--green); }
a { color: inherit; }
.hero {
  padding: 76px 7% 60px;
  max-width: 1000px;
}
.eyebrow { color: var(--green); font-weight: bold; }
h1 { font-size: clamp(38px, 7vw, 64px); line-height: 1.08; }
h1 span { color: var(--green); }
.hero p { color: var(--muted); max-width: 580px; }
.btn {
  display: inline-block;
  background: var(--green);
  color: #111827;
  padding: 12px 18px;
  border-radius: 9px;
  font-weight: bold;
  text-decoration: none;
}
section { padding: 35px 7% 65px; }
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}
.product {
  background: var(--card);
  padding: 23px;
  border: 1px solid #374151;
  border-radius: 15px;
}
.product .symbol { font-size: 36px; }
.price { color: var(--green); font-size: 27px; font-weight: bold; }
.product p, footer p { color: var(--muted); }
.product .btn { width: 100%; text-align: center; }
.note { color: var(--muted); font-size: 13px; }
footer { border-top: 1px solid #374151; border-bottom: 0; }
</style>
</head>
<body>
<header>
  <nav>
    <div class="logo">NEXORA<span>.</span></div>
    <a href="#produtos">Ver produtos ↓</a>
  </nav>
</header>

<main>
  <div class="hero">
    <div class="eyebrow">IDEIAS QUE VIRAM RESULTADOS</div>
    <h1>Aprenda.<br>Crie. <span>Evolua.</span></h1>
    <p>
      Materiais digitais práticos para você organizar sua rotina,
      cuidar melhor do dinheiro e desenvolver novas habilidades.
    </p>
    <a class="btn" href="#produtos">Conhecer os produtos</a>
  </div>

  <section id="produtos">
    <div class="eyebrow">NOSSA COLEÇÃO</div>
    <h2>Pequenas ferramentas. Grandes possibilidades.</h2>
    <div class="products">
      <article class="product">
        <div class="symbol">📅</div>
        <h3>Nexora Planner</h3>
        <p>Planejamento semanal, metas e acompanhamento de hábitos.</p>
        <div class="price">R$ 9,90</div>
        <p class="note">Arquivo digital em PDF.</p>
        <a class="btn" href="COLE_AQUI_LINK_DO_PLANNER">Quero meu planner</a>
      </article>

      <article class="product">
        <div class="symbol">📊</div>
        <h3>Nexora Finance</h3>
        <p>Organize entradas, gastos e metas para economizar.</p>
        <div class="price">R$ 19,90</div>
        <p class="note">Planilha digital.</p>
        <a class="btn" href="COLE_AQUI_LINK_DA_PLANILHA">Quero a planilha</a>
      </article>

      <article class="product">
        <div class="symbol">💻</div>
        <h3>Nexora Freelancer</h3>
        <p>Guia prático com roteiro para buscar clientes e montar portfólio.</p>
        <div class="price">R$ 24,90</div>
        <p class="note">Guia digital em PDF.</p>
        <a class="btn" href="COLE_AQUI_LINK_DO_GUIA">Quero o guia</a>
      </article>
    </div>
    <p class="note">
      Os produtos e preços são demonstrativos até o cadastro
      e a criação dos arquivos finais.
    </p>
  </section>

  <section>
    <h2>Simples, digital e direto ao ponto.</h2>
    <p>Escolha seu material, conclua a compra com segurança
    pela plataforma de pagamento e siga as instruções de acesso
    apresentadas após a confirmação.</p>
  </section>
</main>

<footer>
  <div class="logo">NEXORA<span>.</span></div>
  <p>Ideias que viram resultados.</p>
  <p class="note">
    Adicione aqui seu contato, política de privacidade,
    termos de compra e informações sobre reembolso.
  </p>
  <p class="note">© 2026 Nexora. Todos os direitos reservados.</p>
</footer>
</body>
