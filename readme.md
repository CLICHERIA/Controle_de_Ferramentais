<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>README - Sistema de Gestão de Ferramentais</title>
<style>
  body {
    background-color: #0a0f1a;
    color: #ffffff;
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 0 20px;
  }

  a {
    color: #00eaff;
    text-decoration: none;
  }

  h1, h2, h3 {
    color: #00eaff;
    text-shadow: 0 0 15px #00eaff;
  }

  h1 {
    text-align: center;
    margin-top: 20px;
  }

  .centralizado {
    text-align: center;
    max-width: 900px;
    margin: 0 auto 40px auto;
  }

  .banner img {
    width: 200px;
    display: block;
    margin: 0 auto;
    filter: drop-shadow(0 0 8px #00eaff);
  }

  .badge img {
    margin: 5px;
  }

  .neon-button {
    display: inline-block;
    padding: 12px 30px;
    margin: 20px 0;
    color: #00eaff;
    font-weight: bold;
    font-size: 16px;
    border-radius: 10px;
    background-color: #0d1b2a;
    box-shadow: 0 0 5px #00eaff, 0 0 10px #00eaff, 0 0 20px #00eaff;
    transition: 0.3s ease-in-out;
  }

  .neon-button:hover {
    color: #00ffff;
    box-shadow: 0 0 15px #00eaff, 0 0 30px #00eaff, 0 0 45px #00eaff77;
  }

  hr {
    border:0;
    border-top:1px solid #00eaff44;
    margin: 30px 0;
  }

  pre {
    background-color: #0d1b2a;
    color: #00eaff;
    padding: 15px;
    border-radius: 10px;
    overflow-x: auto;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }

  th, td {
    border: 1px solid #00eaff44;
    padding: 10px;
    text-align: center;
  }

  th {
    background-color: #0d1b2a;
    color: #00eaff;
  }

  td {
    background-color: #111b2a;
  }

  footer {
    text-align: center;
    font-size: 14px;
    color: #777;
    margin-top: 40px;
  }

</style>
</head>
<body>

<div class="centralizado banner">
  <img src="logosovel1337.png" alt="Logo Grupo Sovel da Amazônia">
</div>

<h1>⚙️ Sistema de Gestão de Ferramentais - SGF</h1>
<p class="centralizado"><b>Departamento de Amostras e Clicheria</b><br>Grupo Sovel da Amazônia</p>

<hr>

<h2>📚 Sumário</h2>
<ul>
  <li><a href="#sobre">💡 Sobre o Projeto</a></li>
  <li><a href="#arquitetura">🧩 Arquitetura do Projeto</a></li>
  <li><a href="#tecnologias">🛠️ Tecnologias e Recursos</a></li>
  <li><a href="#equipe">👥 Equipe D.A.C</a></li>
  <li><a href="#acesso">🚀 Instalação e Acesso</a></li>
  <li><a href="#contato">💬 Contato e Sugestões</a></li>
  <li><a href="#licenca">🪪 Licença</a></li>
</ul>

<hr>

<h2 id="sobre">💡 Sobre o Projeto</h2>
<p>
O <b>Sistema de Gestão de Ferramentais (SGF)</b> tem como objetivo <b>automatizar e digitalizar</b> o controle de ferramentais do Departamento de Amostras e Clicheria.<br>
Cada ferramenta possui um <b>QR Code exclusivo</b> contendo informações técnicas e rastreáveis, garantindo eficiência, agilidade e segurança operacional.
</p>

<ul>
  <li>🔹 Gerenciamento completo do ciclo de vida das ferramentas</li>
  <li>🔹 Registro de localização, estado e responsável</li>
  <li>🔹 Relatórios e histórico de movimentações</li>
</ul>

<hr>

<h2 id="arquitetura">🧩 Arquitetura do Projeto</h2>
<pre>
docs/
 ┣ index.html       → Painel inicial e login
 ┣ registrar.html   → Cadastro de ferramentais
 ┣ consultar.html   → Consulta e QR Codes
 ┣ editar.html      → Edição de registros
 ┣ detalhes.html    → Visualização via QR Code
 ┗ logosovel1337.png → Logo principal
</pre>

<hr>

<h2 id="tecnologias">🛠️ Tecnologias e Recursos</h2>
<ul>
  <li>HTML5, CSS3, JavaScript</li>
  <li>QR Code para rastreabilidade</li>
  <li>Painel interativo e responsivo</li>
  <li>Base pronta para integração com banco de dados interno (Firebase)</li>
  <li>Segurança e autenticação de usuários via Firebase Auth</li>
</ul>

<hr>

<h2 id="equipe">👥 Equipe D.A.C</h2>
<table>
  <tr>
    <th>Nome</th>
    <th>Função</th>
  </tr>
  <tr>
    <td>⚡ Samueldson Ferreira</td>
    <td>Supervisor</td>
  </tr>
  <tr>
    <td>📊 Rafaelly Azevedo</td>
    <td>Analista Administrativo</td>
  </tr>
  <tr>
    <td>🔧 Elienson Duarte</td>
    <td>Assistente</td>
  </tr>
  <tr>
    <td>🔧 Gustavo Albuquerque</td>
    <td>Assistente</td>
  </tr>
  <tr>
    <td>🔧 Vanessa Nascimento</td>
    <td>Assistente</td>
  </tr>
</table>

<hr>

<h2 id="acesso">🚀 Instalação e Acesso</h2>
<pre>
1. Clone o repositório:
   git clone https://github.com/seu-usuario/sgf-sovel.git

2. Acesse a pasta:
   cd sgf-sovel/docs

3. Abra o arquivo index.html no navegador.

> 🔐 O acesso ao painel requer autenticação de usuários autorizados pela D.A.C
</pre>
<p class="centralizado">
  <a href="docs/index.html" class="neon-button">Acessar Painel Interativo</a>
</p>

<hr>

<h2 id="contato">💬 Contato e Sugestões</h2>
<p>
Envie ideias e melhorias diretamente para o Departamento de Amostras e Clicheria:<br>
📧 <a href="mailto:dac@sovel.com.br">dac@sovel.com.br</a><br>
📍 Manaus - AM, Brasil
</p>

<hr>

<h2 id="licenca">🪪 Licença</h2>
<p>© 2025 Grupo Sovel da Amazônia – Todos os direitos reservados.<br>
Uso restrito ao Departamento de Amostras e Clicheria.</p>

<footer>
<p>“Eficiência e inovação caminham lado a lado quando trabalhamos com propósito.”<br>
— Equipe D.A.C | Grupo Sovel da Amazônia</p>
</footer>

</body>
</html>
