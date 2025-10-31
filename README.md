<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bem-vindo | Grupo Sovel</title>
  <style>
    /* --- Fundo Neon Dark --- */
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #0a0f1a 0%, #020409 100%);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      overflow: hidden;
    }

    /* --- Animações de entrada --- */
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(-20px);}
      to {opacity: 1; transform: translateY(0);}
    }

    .fade-in {
      animation: fadeIn 1.5s ease forwards;
    }

    /* --- Logo --- */
    img {
      width: 180px;
      filter: drop-shadow(0 0 12px #00eaff);
      margin-bottom: 20px;
    }

    /* --- Títulos --- */
    h1 {
      color: #00eaff;
      text-shadow: 0 0 20px #00eaff;
      margin-bottom: 10px;
      font-size: 2rem;
      animation: fadeIn 1s ease;
    }

    p.subtitle {
      color: #9fd0ff;
      font-size: 1.1rem;
      margin-bottom: 30px;
      animation: fadeIn 1.5s ease;
    }

    /* --- Botão Neon --- */
    .btn-neon {
      display: inline-block;
      padding: 15px 35px;
      font-size: 1.2rem;
      font-weight: bold;
      color: #0a0f1a;
      background: #00c3ff;
      border: 2px solid #00c3ff;
      border-radius: 12px;
      cursor: pointer;
      text-decoration: none;
      text-transform: uppercase;
      box-shadow: 0 0 15px #00c3ff, 0 0 30px #00c3ff44;
      transition: all 0.3s ease;
      animation: fadeIn 2s ease;
    }

    .btn-neon:hover {
      background: #0a0f1a;
      color: #00c3ff;
      box-shadow: 0 0 25px #00eaff, 0 0 50px #00eaff88;
      transform: scale(1.05);
    }

    /* --- Rodapé --- */
    footer {
      position: absolute;
      bottom: 15px;
      font-size: 0.9rem;
      color: #777;
    }

    /* --- Conteúdo do splash --- */
    .content {
      max-width: 700px;
      margin: 0 20px;
      color: #c0dfff;
    }

    .content h2 {
      color: #00bfff;
      text-shadow: 0 0 10px #00eaff;
    }

    .content ul {
      text-align: left;
      padding-left: 20px;
      color: #a9e5ff;
    }

    /* --- Responsivo --- */
    @media (max-width: 600px) {
      h1 { font-size: 1.6rem; }
      .btn-neon { width: 80%; padding: 12px; }
    }
  </style>
</head>
<body>

  <div class="fade-in">
    <img src="../logosovel1337.png" alt="Logo Grupo Sovel">
    <h1>⚙️ Sistema de Gestão de Ferramentais ⚙️</h1>
    <p class="subtitle">Departamento de Amostras e Clicheria - Grupo Sovel da Amazônia</p>

    <div class="content">
      <h2>💡 Sobre o Sistema</h2>
      <p>O sistema digitaliza e automatiza o controle de ferramentais, integrando QR Codes para rastreabilidade completa. Ele permite:</p>
      <ul>
        <li>Gerenciar todo o ciclo de vida das ferramentas</li>
        <li>Registrar e consultar ferramentas rapidamente</li>
        <li>Emitir QR Codes de identificação</li>
        <li>Gerar relatórios e histórico de movimentações</li>
      </ul>
    </div>

    <br>
    <a href="index.html" class="btn-neon">➡️ Entrar no Painel Interativo</a>
  </div>

  <footer>
    <p>© 2025 Grupo Sovel da Amazônia • Departamento de Amostras e Clicheria</p>
  </footer>

</body>
</html>
