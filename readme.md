!-- ====================== --
!-- README - GRUPO SOVEL --
!-- ====================== --

!-- Estilo global --
style
  body {
    background-color #0a0f1a;  fundo preto site inteiro 
    margin 0;
    padding 0;
    color #ffffff;
    font-family 'Segoe UI', sans-serif;
  }

  html, body {
    width 100%;
    height 100%;
  }

  a {
    color #00eaff;
    text-decoration none;
  }

   Container da logo para glow seguro 
  .logo-container {
    display inline-block;
    background transparent;
    padding 0;
    margin 0;
    filter drop-shadow(0 0 8px #00eaff);  brilho neon 
  }

  img.logo {
    display block;
    margin 0 auto;
    background-color transparent;
    vertical-align middle;
  }

   Neon Button 
  .neon-button {
    display inline-block;
    padding 15px 35px;
    color #00eaff;
    text-decoration none;
    font-weight bold;
    font-size 16px;
    border-radius 10px;
    background-color #0d1b2a;
    box-shadow
      0 0 5px #00eaff,
      0 0 10px #00eaff,
      0 0 20px #00eaff,
      0 0 40px #00eaff55;
    transition 0.3s ease-in-out;
    animation neonPulse 1.5s infinite alternate;
  }

  .neon-buttonhover {
    color #00ffff;
    box-shadow
      0 0 10px #00eaff,
      0 0 20px #00eaff,
      0 0 30px #00eaff,
      0 0 50px #00eaff77;
  }

  @keyframes neonPulse {
    0%, 100% {
      box-shadow
        0 0 5px #00eaff,
        0 0 10px #00eaff,
        0 0 20px #00eaff;
    }
    50% {
      box-shadow
        0 0 15px #00eaff,
        0 0 30px #00eaff,
        0 0 45px #00eaff77;
    }
  }

   Neon animado para os cards da equipe 
  .neon-card {
    background #0a0f1a;
    color #ffffff;
    padding 25px;
    border-radius 20px;
    text-align center;
    min-width 200px;
    box-shadow
      0 0 10px #00eaff,
      0 0 20px #00eaff55;
    animation neonCardPulse 2s infinite alternate;
    transition transform 0.3s ease-in-out;
  }

  .neon-cardhover {
    transform scale(1.05);
    box-shadow
      0 0 20px #00eaff,
      0 0 40px #00eaff77,
      0 0 60px #00eaff99;
  }

  @keyframes neonCardPulse {
    0%, 100% {
      box-shadow
        0 0 5px #00eaff,
        0 0 15px #00eaff22;
    }
    50% {
      box-shadow
        0 0 15px #00eaff,
        0 0 30px #00eaff44;
    }
  }

  .neon-card h3 {
    margin 0 0 10px 0;
    color #00eaff;
    text-shadow 0 0 8px #00eaff;
  }

  .neon-card p {
    margin 0;
  }

   Centralização geral das seções 
  .centralizado {
    text-align center;
    max-width 900px;
    margin 0 auto;
  }

   Pre centralizado 
  .pre-centralizado {
    display inline-block;
    text-align left;
    background-color #0d1b2a;
    color #00eaff;
    padding 20px;
    border-radius 10px;
    box-shadow 0 0 20px #00eaff22;
  }
style

!-- ====================== --
!-- Bloco Logo + Título --
!-- ====================== --
div style=background-color#0a0f1a; padding40px; border-radius20px; box-shadow0 0 30px #00eaff55; text-aligncenter;

  !-- Logo centralizada em container transparente com glow --
  div class=logo-container
    img src=logosovel1337.png alt=Logo Grupo Sovel da Amazônia width=200 class=logo 
  div

  !-- Título neon --
  h1 style=color#00eaff; text-shadow0 0 20px #00eaff; margin-top20px;
    ⚙️ Sistema de Gestão de Ferramentais ⚙️
  h1

  !-- Subtítulo --
  p style=color#9fd0ff; font-size18px; margin-top10px;
    bDepartamento de Amostras e Clicheriabbr
    bGrupo Sovel da Amazôniab
  p

  !-- Badges --
  p style=margin-top20px;
    img src=httpsimg.shields.iobadgeStatus-Em%20Operação-00ffccstyle=for-the-badge&logo=serverless&logoColor=white alt=Status
    img src=httpsimg.shields.iobadgeVersão-1.0.0-007bffstyle=for-the-badge&logo=semanticrelease&logoColor=white alt=Versão
    img src=httpsimg.shields.iobadgeAtualizado-Outubro%2F2025-333333style=for-the-badge&logo=github&logoColor=white alt=Última atualização
    img src=httpsimg.shields.iobadgeTecnologia-QR--Code%20%7C%20Gestão--Digital-0099ffstyle=for-the-badge&logo=qrcode&logoColor=white alt=Tecnologia
  p

  !-- Botão Painel Interativo neon animado --
  p style=margin-top20px;
    a href=docsindex.html target=_blank class=neon-button
      Acessar Painel Interativo
    a
  p

div

hr style=border0; border-top1px solid #00eaff44; margin30px 0;

!-- ====================== --
!-- Conteúdo Centralizado --
!-- ====================== --
div class=centralizado

  !-- Sobre o Projeto --
  h2 style=color#00bfff; text-shadow0 0 15px #00eaff;💡 Sobre o Projetoh2

  p style=color#c0dfff; font-size16px; line-height1.6;
    O bSistema de Gestão de Ferramentaisb tem como propósito bautomatizar e digitalizarb o controle de ferramentais do bDepartamento de Amostras e Clicheriab.br
    Através de uma interface moderna e integração com bQR Codesb, o sistema gerencia btodo o ciclo de vida das ferramentasb, desde o recebimento até a substituição.
  p

  p style=color#a9e5ff; font-size16px; line-height1.6;
    🔹 Cada ferramenta possui um bQR Code exclusivob contendo informações técnicas e rastreáveis.br
    🔹 Foco em beficiência, agilidade e segurança operacionalb.br
    🔹 Desenvolvido com base em binovação tecnológica e melhoria contínuab.
  p

  hr style=border0; border-top1px solid #00eaff44; margin30px 0;

  !-- Grupo Sovel --
  h2 style=color#00bfff;🏢 Grupo Sovel da Amazôniah2
  p style=color#c0dfff;bDepartamento de Amostras e Clicheriabp

  hr style=border0; border-top1px solid #00eaff44; margin30px 0;

  !-- Equipe D.A.C --
  h2 style=color#00bfff; text-shadow0 0 20px #00eaff; margin-bottom30px;👥 Equipe D.A.Ch2

  div style=displayflex; flex-wrapwrap; justify-contentcenter; gap30px;
    div class=neon-card
      h3⚡ Samueldson Ferreirah3
      p🛡️ Supervisorp
    div
    div class=neon-card
      h3📊 Rafaelly Azevedoh3
      p💼 Analista Administrativop
    div
    div class=neon-card
      h3🔧 Elienson Duarteh3
      p🛠️ Assistentep
    div
    div class=neon-card
      h3🔧 Gustavo Albuquerqueh3
      p🛠️ Assistentep
    div
    div class=neon-card
      h3🔧 Vanessa Nascimentoh3
      p🛠️ Assistentep
    div
  div

  hr style=border0; border-top1px solid #00eaff44; margin30px 0;

  !-- Tecnologias --
  h2 style=color#00bfff;🛠️ Tecnologias e Recursosh2

  div style=background-color#0a0f1a; color#00eaff; padding20px; border-radius10px; text-alignleft; max-width600px; margin0 auto; white-spacepre-wrap;
- Interface responsiva (HTML5CSS3)
- Controle de ferramentais via QR Code
- Painel interativo e intuitivo
- Relatórios e histórico de movimentações
- Base pronta para integração com banco de dados interno
div


  hr style=border0; border-top1px solid #00eaff44; margin30px 0;

  !-- Contato --
  h2 style=color#00bfff;💬 Contato e Sugestõesh2
  p style=color#c0dfff; font-size16px; line-height1.6;
    Envie suas ideias e melhorias diretamente para o bDepartamento de Amostras e Clicheriab.brbr
    📧 a href=mailtodac@sovel.com.brdac@sovel.com.brabr
    📍 Manaus - AM, Brasil
  p

  hr style=border0; border-top1px solid #00eaff44; margin30px 0;

  p style=font-styleitalic; color#66d9ff;
    “Eficiência e inovação caminham lado a lado quando trabalhamos com propósito.”
  p

  p style=color#00eaff;b— Equipe D.A.C  Grupo Sovel da Amazôniabp

  sub style=color#777;© 2025 Grupo Sovel da Amazônia • Departamento de Amostras e Clicheriasub

div
