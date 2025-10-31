<!-- ====================== -->
<!-- README - GRUPO SOVEL -->
<!-- ====================== -->

<!-- Estilo global -->
<style>
  body {
    background-color: #0a0f1a; /* fundo preto site inteiro */
    margin: 0;
    padding: 0;
    color: #ffffff;
    font-family: 'Segoe UI', sans-serif;
  }

  html, body {
    width: 100%;
    height: 100%;
  }

  a {
    color: #00eaff;
    text-decoration: none;
  }

  /* Container da logo para glow seguro */
  .logo-container {
    display: inline-block;
    background: transparent;
    padding: 0;
    margin: 0;
    filter: drop-shadow(0 0 8px #00eaff); /* brilho neon */
  }

  img.logo {
    display: block;
    margin: 0 auto;
    background-color: transparent;
    vertical-align: middle;
  }

  /* Neon Button */
  .neon-button {
    display: inline-block;
    padding: 15px 35px;
    color: #00eaff;
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
    border-radius: 10px;
    background-color: #0d1b2a;
    box-shadow:
      0 0 5px #00eaff,
      0 0 10px #00eaff,
      0 0 20px #00eaff,
      0 0 40px #00eaff55;
    transition: 0.3s ease-in-out;
    animation: neonPulse 1.5s infinite alternate;
  }

  .neon-button:hover {
    color: #00ffff;
    box-shadow:
      0 0 10px #00eaff,
      0 0 20px #00eaff,
      0 0 30px #00eaff,
      0 0 50px #00eaff77;
  }

  @keyframes neonPulse {
    0%, 100% {
      box-shadow:
        0 0 5px #00eaff,
        0 0 10px #00eaff,
        0 0 20px #00eaff;
    }
    50% {
      box-shadow:
        0 0 15px #00eaff,
        0 0 30px #00eaff,
        0 0 45px #00eaff77;
    }
  }

  /* Neon animado para os cards da equipe */
  .neon-card {
    background: #0a0f1a;
    color: #ffffff;
    padding: 25px;
    border-radius: 20px;
    text-align: center;
    min-width: 200px;
    box-shadow:
      0 0 10px #00eaff,
      0 0 20px #00eaff55;
    animation: neonCardPulse 2s infinite alternate;
    transition: transform 0.3s ease-in-out;
  }

  .neon-card:hover {
    transform: scale(1.05);
    box-shadow:
      0 0 20px #00eaff,
      0 0 40px #00eaff77,
      0 0 60px #00eaff99;
  }

  @keyframes neonCardPulse {
    0%, 100% {
      box-shadow:
        0 0 5px #00eaff,
        0 0 15px #00eaff22;
    }
    50% {
      box-shadow:
        0 0 15px #00eaff,
        0 0 30px #00eaff44;
    }
  }

  .neon-card h3 {
    margin: 0 0 10px 0;
    color: #00eaff;
    text-shadow: 0 0 8px #00eaff;
  }

  .neon-card p {
    margin: 0;
  }
</style>

<!-- ====================== -->
<!-- Bloco Logo + Título -->
<!-- ====================== -->
<div style="background-color:#0a0f1a; padding:40px; border-radius:20px; box-shadow:0 0 30px #00eaff55; text-align:center;">

  <!-- Logo centralizada em container transparente com glow -->
  <div class="logo-container">
    <img src="logosovel1337.png" alt="Logo Grupo Sovel da Amazônia" width="200" class="logo" />
  </div>

  <!-- Título neon -->
  <h1 style="color:#00eaff; text-shadow:0 0 20px #00eaff; margin-top:20px;">
    ⚙️ Sistema de Gestão de Ferramentais ⚙️
  </h1>

  <!-- Subtítulo -->
  <p style="color:#9fd0ff; font-size:18px; margin-top:10px;">
    <b>Departamento de Amostras e Clicheria</b><br>
    <b>Grupo Sovel da Amazônia</b>
  </p>

  <!-- Badges -->
  <p style="margin-top:20px;">
    <img src="https://img.shields.io/badge/Status-Em%20Operação-00ffcc?style=for-the-badge&logo=serverless&logoColor=white" alt="Status">
    <img src="https://img.shields.io/badge/Versão-1.0.0-007bff?style=for-the-badge&logo=semanticrelease&logoColor=white" alt="Versão">
    <img src="https://img.shields.io/badge/Atualizado-Outubro%2F2025-333333?style=for-the-badge&logo=github&logoColor=white" alt="Última atualização">
    <img src="https://img.shields.io/badge/Tecnologia-QR--Code%20%7C%20Gestão--Digital-0099ff?style=for-the-badge&logo=qrcode&logoColor=white" alt="Tecnologia">
  </p>

  <!-- Botão Painel Interativo neon animado -->
  <p align="center" style="margin-top:20px;">
    <a href="docs/index.html" target="_blank" class="neon-button">
      Acessar Painel Interativo
    </a>
  </p>

</div>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<!-- ====================== -->
<!-- Sobre o Projeto -->
<!-- ====================== -->
<h2 style="color:#00bfff; text-shadow:0 0 15px #00eaff;">💡 Sobre o Projeto</h2>

<p align="justify" style="max-width:800px; color:#c0dfff;">
  O <b>Sistema de Gestão de Ferramentais</b> tem como propósito <b>automatizar e digitalizar</b> o controle de ferramentais do <b>Departamento de Amostras e Clicheria</b>.  
  Através de uma interface moderna e integração com <b>QR Codes</b>, o sistema gerencia <b>todo o ciclo de vida das ferramentas</b>, desde o recebimento até a substituição.
</p>

<p style="max-width:800px; color:#a9e5ff;">
  🔹 Cada ferramenta possui um <b>QR Code exclusivo</b> contendo informações técnicas e rastreáveis.<br>
  🔹 Foco em <b>eficiência, agilidade e segurança operacional</b>.<br>
  🔹 Desenvolvido com base em <b>inovação tecnológica e melhoria contínua</b>.
</p>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<!-- ====================== -->
<!-- Grupo Sovel -->
<!-- ====================== -->
<h2 style="color:#00bfff;">🏢 Grupo Sovel da Amazônia</h2>
<p style="color:#c0dfff;"><b>Departamento de Amostras e Clicheria</b></p>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<!-- ====================== -->
<!-- Equipe D.A.C -->
<!-- ====================== -->
<h2 style="color:#00bfff; text-shadow:0 0 20px #00eaff; text-align:center; margin-bottom:30px;">👥 Equipe D.A.C</h2>

<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:30px;">
  <div class="neon-card">
    <h3>⚡ Samueldson Ferreira</h3>
    <p>🛡️ Supervisor</p>
  </div>
  <div class="neon-card">
    <h3>📊 Rafaelly Azevedo</h3>
    <p>💼 Analista Administrativo</p>
  </div>
  <div class="neon-card">
    <h3>🔧 Elienson Duarte</h3>
    <p>🛠️ Assistente</p>
  </div>
  <div class="neon-card">
    <h3>🔧 Gustavo Albuquerque</h3>
    <p>🛠️ Assistente</p>
  </div>
  <div class="neon-card">
    <h3>🔧 Vanessa Nascimento</h3>
    <p>🛠️ Assistente</p>
  </div>
</div>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<!-- Tecnologias -->
<h2 style="color:#00bfff;">🛠️ Tecnologias e Recursos</h2>

<pre style="background-color:#0d1b2a; color:#00eaff; padding:20px; border-radius:10px; box-shadow:0 0 20px #00eaff22; text-align:left;">
- Interface responsiva (HTML5/CSS3)
- Controle de ferramentais via QR Code
- Painel interativo e intuitivo
- Relatórios e histórico de movimentações
- Base pronta para integração com banco de dados interno
</pre>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<!-- Contato -->
<h2 style="color:#00bfff;">💬 Contato e Sugestões</h2>
<p style="color:#c0dfff;">
  Envie suas ideias e melhorias diretamente para o <b>Departamento de Amostras e Clicheria</b>.<br><br>
  📧 <a href="mailto:dac@sovel.com.br">dac@sovel.com.br</a><br>
  📍 Manaus - AM, Brasil
</p>

<hr style="border:0; border-top:1px solid #00eaff44; margin:30px 0;">

<p style="font-style:italic; color:#66d9ff;">
  “Eficiência e inovação caminham lado a lado quando trabalhamos com propósito.”
</p>

<p style="color:#00eaff;"><b>— Equipe D.A.C | Grupo Sovel da Amazônia</b></p>

<sub style="color:#777;">© 2025 Grupo Sovel da Amazônia • Departamento de Amostras e Clicheria</sub>
