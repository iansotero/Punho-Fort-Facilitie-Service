<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Punho Fort Facilities Services</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f6f8;
    color: #333;
}

/* HEADER FIXO */
header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #ffffff;
    border-bottom: 1px solid #ddd;
    padding: 12px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
    box-sizing: border-box;
}

.logo {
    display: flex;
    align-items: center;
}

header img {
    height: 70px;
}

header h1 {
    margin-left: 15px;
    font-size: 22px;
    color: #1f2933;
}

/* MENU */
nav {
    display: flex;
    gap: 25px;
}

nav a {
    text-decoration: none;
    color: #1f2933;
    font-size: 13px;
    text-align: center;
}

nav span {
    display: block;
    font-size: 20px;
}

/* CONTAINER */
.container {
    max-width: 1100px;
    margin: 140px auto 60px;
    padding: 0 20px;
}

h2 {
    color: #1f2933;
    margin-bottom: 10px;
}

p {
    line-height: 1.7;
    font-size: 16px;
}

/* BOTÕES */
.botoes {
    margin: 40px 0;
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.botao {
    text-decoration: none;
    padding: 15px 28px;
    border-radius: 8px;
    font-weight: bold;
    font-size: 15px;
    color: #ffffff;
}

.botao-comercial {
    background-color: #0f4c81;
}

.botao-comercial:hover {
    background-color: #0c3c66;
}

.botao-rh {
    background-color: #1f6f5c;
}

.botao-rh:hover {
    background-color: #185a4b;
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 25px;
    margin-top: 40px;
}

.card {
    background-color: #ffffff;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    overflow: hidden;
    text-align: center;
}

.card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
}

.card-content {
    padding: 20px;
}

.card h3 {
    margin-top: 0;
    color: #0f4c81;
}

/* SERVIÇOS */
.servicos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    margin-top: 40px;
}

.servico-card {
    background: #e9edf1;
    border-radius: 14px;
    padding: 25px;
    text-align: center;
}

.icon {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #0f4c81;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 28px;
    margin: 0 auto 15px;
}

.servico-card h3 {
    margin-bottom: 10px;
    color: #0f4c81;
}

/* FOOTER */
footer {
    background-color: #1f2933;
    color: #ffffff;
    text-align: center;
    padding: 22px;
    margin-top: 70px;
    font-size: 14px;
}

/* 🔧 CORREÇÃO PARA ÂNCORAS COM HEADER FIXO */
:target {
    scroll-margin-top: 120px;
}
/* LOGIN MODAL */
.login-modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0,0,0,0.6);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 2000;
}

.login-box {
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    width: 100%;
    max-width: 360px;
    text-align: center;
}

.login-box h2 {
    margin-bottom: 20px;
    color: #0f4c81;
}

.login-box input {
    width: 100%;
    padding: 12px;
    margin-bottom: 12px;
    border-radius: 6px;
    border: 1px solid #ccc;
}

.login-box button {
    width: 100%;
    padding: 12px;
    background: #0f4c81;
    color: #fff;
    border: none;
    border-radius: 6px;
    font-weight: bold;
    cursor: pointer;
}

.login-box button:hover {
    background: #0c3c66;
}

.login-box a {
    display: block;
    margin-top: 15px;
    color: #555;
    text-decoration: none;
    font-size: 14px;
}
  
</style>
</head>

<body>

<header>
    <div class="logo">
        <img src="https://media.licdn.com/dms/image/v2/C4D0BAQEmT-m-5CKL9w/company-logo_200_200/company-logo_200_200/0/1630498690652?e=2147483647&v=beta&t=jqtSO1BnHPlYqx6y9RWFzABdLUBLTRFCjRcwSpH4ocQ">
        <h1>Punho Fort Facilities Service</h1>
    </div>

    <nav>
        <a href="#servicos"><span>🧰</span>Serviços</a>
        <a href="#clientes"><span>🤝</span>Clientes</a>
        <a href="#"><span>❓</span>Dúvidas</a>
        <a href="#"><span>👷</span>Trabalhe Conosco</a>
        <a href="javascript:void(0)" onclick="abrirLogin()">
          <span>🏠</span>Login</a>
    </nav>
</header>

<div class="container">

<h2>Quem Somos</h2>

<p>
A <strong>Punho Fort</strong> foi criada com o objetivo da prestação de serviços de
<strong>Limpeza, Conservação, Higienização e Desinfecção Ambiental</strong>,
<strong>Manutenção Predial e Industrial</strong>, <strong>Manutenção e Reforma de Telhados</strong>,
<strong>Alpinismo Industrial e Predial</strong> e <strong>Carga e Descarga</strong>.
</p>

<p>
Nosso trabalho consiste em identificar, desenvolver e gerenciar uma solução adequada
e integrada ao perfil da sua empresa e dos seus colaboradores.
</p>

<p>
Contamos com mais de <strong>20 anos de experiência</strong>, atendendo clientes
exigentes com foco no trinômio:
<strong>Eficiência • Segurança • Economia</strong>.
</p>

<div class="botoes">
    <a class="botao botao-comercial"
       href="https://wa.me/5581998260232"
       target="_blank">
        💼 Falar com o Comercial
    </a>
  
    <a class="botao botao-rh"
       href="https://wa.me/5581981807474"
       target="_blank">
        👷 Trabalhe Conosco (RH)
    </a>
</div>

<h2>Áreas de Atuação</h2>

<div class="cards">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">
        <div class="card-content">
            <h3>Corporativo</h3>
            <p>Soluções completas para empresas, escritórios e indústrias.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1588072432836-e10032774350">
        <div class="card-content">
            <h3>Educação</h3>
            <p>Ambientes limpos, seguros e adequados ao aprendizado.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1586773860418-d37222d8fce3">
        <div class="card-content">
            <h3>Saúde</h3>
            <p>Rigorosos padrões de higienização e controle ambiental.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
        <div class="card-content">
            <h3>Condomínio</h3>
            <p>Conservação, manutenção e bem-estar.</p>
        </div>
    </div>
</div>

<h2 id="servicos">Nossos Serviços</h2>

<div class="servicos">
    <div class="servico-card"><div class="icon">🧹</div><h3>Limpeza</h3><p>Descreva aqui</p></div>
    <div class="servico-card"><div class="icon">🏢</div><h3>Manutenção Predial</h3><p>Descreva aqui</p></div>
    <div class="servico-card"><div class="icon">🧗</div><h3>Alpinismo Industrial e Predial</h3><p>Descreva aqui</p></div>
    <div class="servico-card"><div class="icon">🏭</div><h3>Manutenção Predial e Industrial</h3><p>Descreva aqui</p></div>
    <div class="servico-card"><div class="icon">🛠️</div><h3>Manutenção e Reforma de Telhados</h3><p>Descreva aqui</p></div>
    <div class="servico-card"><div class="icon">🚚</div><h3>Carga e Descarga</h3><p>Descreva aqui</p></div>
</div>

</div>

<section id="clientes">
<div class="container">

<h2>Nossos Clientes</h2>

<p style="text-align:center; max-width:900px; margin:20px auto 40px;">
<strong>ORGULHOSAMENTE, RESERVAMOS ESTE ESPAÇO PARA SUA MARCA!</strong>
</p>

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(180px, 1fr)); gap:30px; justify-items:center;">
    <img src="https://th.bing.com/th/id/OIP.iqYYFlrsUXZwJq2BH3q3QQAAAA?w=199&h=180">
    <img src="https://tse1.mm.bing.net/th/id/OIP.snl3ASJA8rdvysNUFn5aggAAAA?w=206&h=206">
    <img src="https://th.bing.com/th/id/OIP.pQJb6PC0u_flG12seBOFNQHaFj?w=198&h=180">
    <img src="https://th.bing.com/th/id/OIP.TmLRNemTdNMy3g0mLUcUgwHaE8?w=251&h=180">
</div>

</div>
</section>
<!-- TELA DE LOGIN -->
<div id="loginModal" class="login-modal">

    <div class="login-box">
        <h2>Área Restrita</h2>

        <input type="text" placeholder="Usuário">
        <input type="password" placeholder="Senha">

        <button>Entrar</button>

        <a href="javascript:void(0)" onclick="fecharLogin()">Fechar</a>
    </div>

</div>
  <script>
function abrirLogin() {
    document.getElementById("loginModal").style.display = "flex";
}

function fecharLogin() {
    document.getElementById("loginModal").style.display = "none";
}
</script>


<footer>
© 2025 Punho Fort Facilities Services<br>
Eficiência • Segurança • Economia<br>
Rua Barão de Água Branca, 521 - Imbiribeira - Recife/PE - 51160-300<br>
CNPJ: 18.253.970/0001-64
</footer>

</body>
</html>

