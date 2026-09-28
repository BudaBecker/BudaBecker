<h1 align="center">Gabriel Becker</h1>

<p align="center">Ciência da Computação · Backend em Python e Java</p>

<p align="center">
  <img src="https://img.shields.io/badge/Bras%C3%ADlia%E2%80%93DF-%F0%9F%87%A7%F0%9F%87%B7-0a66c2?style=for-the-badge" alt="Localização" />
  <img src="https://img.shields.io/badge/Aberto%20a-vagas%20j%C3%BAnior-2ea44f?style=for-the-badge" alt="Disponibilidade" />
  &nbsp;
  <a href="https://www.linkedin.com/in/gabriel-becker-cidral/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:dev.gabriel.becker@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

Estudante de **Ciência da Computação** no UniCEUB (2024–2028), com 7 semestres anteriores em
Engenharia Mecatrônica na USP. Desenvolvo backend em **Python** (Django, Django REST Framework)
e **Java** (Spring Boot), com PostgreSQL, testes automatizados e CI em GitHub Actions. Front-end
é complementar.

O TransWeb e o HarmoniClub, dois sistemas em que trabalho, rodam em um servidor que montei a
partir de um PC sem uso, com Ubuntu Server, Docker e nginx. Programo com agentes de IA
(Claude Code e Codex): escrevo as regras de cada projeto em `AGENTS.md` e uso skills e
subagentes próprios, integrados a outras ferramentas via MCP.

---

### Sistemas principais

Os repositórios são privados: o TransWeb foi feito para um cliente, e o HarmoniClub é de equipe.

**TransWeb — backoffice de vendas e comissionamento** · Python, Django REST Framework,
PostgreSQL, Next.js · com outro desenvolvedor

- Em uso por uma corretora de planos de saúde: corretores, catálogo de produtos, regras de
  comissionamento por vigência, vendas, faturamento e recebíveis.
- Minha parte: usuários e **autenticação JWT** com quatro perfis de acesso, **trilha de
  auditoria** (quem alterou, quando, valor anterior e novo), recebíveis, faturamento e a
  documentação técnica.
- Desenvolvimento por pull request, com CI em GitHub Actions. Roda no servidor próprio.

**HarmoniClub — plataforma de educação musical** · Java 21, Spring Boot, PostgreSQL, Angular ·
em equipe, sou responsável pelo backend e pela infraestrutura

- API REST com autenticação JWT e autorização por papéis. A dificuldade e os atributos da
  tablatura são calculados no servidor a partir da notação, nunca aceitos do cliente.
- Paginação e filtros, N+1 resolvido com `JOIN FETCH`, schema versionado com Flyway e testes de
  integração contra PostgreSQL real (Testcontainers), com CI em GitHub Actions. Roda no
  servidor próprio.

**Servidor próprio** · Ubuntu Server, Docker, nginx — montei a partir de um PC sem uso; hospeda
o TransWeb e o HarmoniClub.

---

### Projetos públicos

| Projeto | Sobre | Stack |
| :--- | :--- | :--- |
| **[Motor de Xadrez](https://github.com/BudaBecker/AI-chess-bot)** | Engine em Java puro: regras completas, geração de lances legais, notação algébrica com desambiguação e exportação PGN. O bot com Minimax e poda alfa-beta ainda não existe: é o próximo passo | `Java` `Swing` |
| **[LinkPulse](https://github.com/BudaBecker/link-pulse)** | Encurtador de URLs com analytics por canal, da disciplina de Bancos de Dados NoSQL. Em desenvolvimento | `Redis` `Cassandra` |
| **[Física Computacional](https://github.com/BudaBecker/python-physics)** | Simulações construídas do zero — pêndulo duplo, três corpos, ray tracing — sem biblioteca de física | `Python` `NumPy` `Pygame` |
| **[Ordenação em C/SDL3](https://github.com/BudaBecker/SDL3-sorting-C)** | Visualizador de algoritmos de ordenação com áudio, um passo por quadro | `C` `SDL3` |
| **[Persona](https://github.com/BudaBecker/persona-webpage)** | Chatbot de restaurante: respostas por regras com *fallback* para GPT e reservas gravadas em MySQL | `Python` `Flask` `OpenAI` |

**PhotoOne — CRM para fotógrafos** · Projeto Integrador (UniCEUB), equipe de 4, Scrum — o
projeto está na fase de documentação e planejamento, ainda sem código do CRM. Escrevo a maior
parte dos registros de sprint, do backlog priorizado por MoSCoW, das decisões de arquitetura
(ADRs) e das atas; o acompanhamento é feito por issues, milestones e pull requests.

---

### Experiência

**Aluno pesquisador — IA aplicada ao Direito** · UnB, em parceria com o TJGO · desde mai/2026
— triagem e classificação de documentos jurídicos sensíveis em Python, com processamento de
linguagem natural.

**Responsável de TI e Apoio Administrativo** · À La Vontê Pizzaria · mar/2026 – ago/2026 —
site institucional em Django, com painel administrativo que a própria equipe opera, imagens em
CDN (Cloudinary) e CI que valida migrações, testes e configuração de produção a cada push; DRE
gerencial semanal das duas lojas automatizada em planilhas e Python, com manual para o
operador; TI das duas unidades.

**Monitor de Programação** · UniCEUB · 2025 – 2026.1 — apoio a estudantes em lógica de
programação, algoritmos e estruturas de dados.

---

### Stack

| | |
| :--- | :--- |
| **Linguagens** | Python · Java · SQL · C · JavaScript/TypeScript |
| **Backend** | Django · Django REST Framework · Spring Boot · FastAPI · Flask · API REST · JWT |
| **Bancos de dados** | PostgreSQL · MySQL · SQLite · Flyway |
| **Testes e entrega** | Django TestCase · JUnit · Testcontainers · Git/GitHub com pull request · GitHub Actions |
| **Infraestrutura** | Linux (Ubuntu Server) · Docker · nginx · Google Cloud (certificação de fundamentos) |
| **Agentes de IA** | Claude Code · Codex · `AGENTS.md` · skills e subagentes via MCP |
| **Front-end (complementar)** | Angular · React · Next.js |
