<h1 align="center">Gabriel Dias Ponsoni</h1>

<p align="center">
  Desenvolvedor web · Sistemas de Informação na UNICAMP<br>
  Java, JavaScript/TypeScript, Python e SQL
</p>

<p align="center">
  <a href="https://linkedin.com/in/GDPonsoni"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-GDPonsoni-0A66C2"></a>
  <a href="mailto:gdponsoni@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-gdponsoni%40gmail.com-D14836?logo=gmail&logoColor=white"></a>
</p>

---

## Sobre

Sou formado em Análise e Desenvolvimento de Sistemas (TADS) e estou cursando Sistemas de Informação, ambos na UNICAMP. Trabalho com desenvolvimento web full stack e já fiz pesquisa aplicada em IoT e inteligência artificial. Minha experiência vai de APIs REST e bancos relacionais até séries temporais e dashboards.

Fora do trabalho, toco projetos próprios: dois aplicativos web full stack e um jogo mobile, descritos abaixo.

## Trabalho atual

**Desenvolvedor e Suporte Web Júnior, SIL Tecnologia em Software (2025 – atual)**
Desenvolvo, refatoro e dou suporte a sistemas tributários usados por administrações municipais.

- Aplicações web em Java e JavaScript, com APIs REST sobre Microsoft SQL Server.
- Relatórios dinâmicos com JasperSoft, XML e Java, a partir de extração e formatação de dados.
- Investigação e correção de problemas em produção (suporte nível 2/3).

## Projetos

### Projetos próprios

**[Album-fig](https://github.com/GDPonsoni/Album-fig): álbum de figurinhas da calourada** · em desenvolvimento

Álbum digital em que cada organização estudantil tem suas páginas e os calouros completam a coleção abrindo pacotes, resgatando códigos e trocando repetidas ao vivo.

- Sorteio dos pacotes feito no servidor, com gaveta de três espaços abastecida por um timer.
- Trocas em tempo real por WebSocket, por QR ou link, com aceite dos dois lados.
- Painel administrativo para organizações, figurinhas, raridades, pacotes, códigos, parâmetros e métricas.
- Testes automatizados no backend, roteiro ponta a ponta em tela de celular e teste de carga.
- Preparado para deploy no Render com Docker, banco no Neon e imagens em bucket privado no Cloudflare R2.

`React` `Vite` `TypeScript (PWA)` `FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL`

**[RepPlus](https://github.com/GDPonsoni/RepPlus): organização de república**

Aplicação web modular para a rotina de uma república, em que cada casa liga só os módulos que usa.

- Escala de limpeza com rodízio determinístico, folgas automáticas e regra do banheiro da suíte.
- Agenda conjunta, lista de compras, atas de reunião, cadastro de moradores e finanças com divisão de despesas.
- Cofre de senhas criptografado no próprio aparelho (AES-256).
- Publicado no Render, com banco Postgres no Neon e imagens no Cloudflare R2.
- Parti da escala de limpeza criada pelo [Leonardo](https://github.com/LeonardoRodriSilva): reestruturei o app em módulos, migrei o banco do Supabase para o Neon e desenvolvi os módulos novos.

`Node.js` `Express` `JavaScript (módulos ES, sem build)` `PostgreSQL`

**[Nucleon Squad](https://github.com/GDPonsoni/nucleon-squad): shoot 'em up mobile** · em teste

Bullet hell vertical para Android em que soltar o dedo deixa o jogo em câmera lenta, e é nesse momento que se troca a nave do esquadrão.

- Seis naves (esquadrão de quatro), armas com cinco níveis e especial que recarrega com o tempo.
- Sete tipos de inimigos, quatro chefes com fases de ataque e quatro capítulos com treze fases.
- Seletor de fases com desbloqueio, recordes salvos no aparelho e textos em PT-BR e EN.
- Parâmetros centralizados, dados do jogo fora do código e pooling de projéteis. O design está documentado em um GDD. A arte ainda é provisória.

`Godot 4` `GDScript`

### Em grupo

**[Delícias da Lú](https://github.com/doceriadeliciasdaluoficial-wq/delicias-da-lu-frontend): front-end de e-commerce de uma doceria** · em dupla

Site com cardápio, carrinho, montagem do pedido de bolo e painel administrativo.

- Montagem do pedido (Cake Builder) e geração da mensagem de WhatsApp.
- Painel administrativo e adaptação da experiência para celular.
- Docker, nginx e build no Google Cloud Build.
- Início da integração com o backend.

`React` `Tailwind CSS` `Vite` `Docker`

**[Campo Minado](https://github.com/LuizHFJesus/minesweeper): jogo web em grupo (2024)**

Campo minado com contas de usuário, histórico de partidas, ranking e modo personalizado. Fiz parte do front-end: navegação, tela de seleção de jogo, jogo personalizado, página do jogo e ranking.

`HTML` `CSS` `JavaScript` `PHP`

## Pesquisa

**Calçado inteligente para análise de marcha (IFSP Guarulhos, 2020 – 2022).** Como aluno pesquisador, trabalhei em um dispositivo vestível de IoT para pré-diagnosticar marchas patológicas em tempo real: modelo em lógica fuzzy (Python), telemetria em InfluxDB, dashboards no Grafana e sensores com microcontroladores em C/C++.

## Tecnologias

**Linguagens**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-555555)

**Web e back-end**<br>
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

**Dados**<br>
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![JasperSoft](https://img.shields.io/badge/JasperSoft-555555)

**Ferramentas**<br>
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?logo=godotengine&logoColor=white)

Também: HTML e CSS, APIs REST, MVC, Design Patterns, Clean Code, metodologias ágeis e deploy no Render, com Neon e Cloudflare R2.

## Formação

- **Bacharelado em Sistemas de Informação**, UNICAMP (2026 – 2028, previsto)
- **Tecnologia em Análise e Desenvolvimento de Sistemas**, UNICAMP (2023 – 2026)
- **Ensino Médio Integrado ao Técnico em Mecatrônica**, IFSP Guarulhos (2019 – 2022)
