<!-- ══════════════════════ IDIOMAS / LANGUAGES ══════════════════════ -->
<div align="center">
<a href="README.md"><img src="https://img.shields.io/badge/Português-1987F0?style=for-the-badge" alt="Português"/></a>
<a href="README.en.md"><img src="https://img.shields.io/badge/English-555555?style=for-the-badge" alt="English"/></a>
<a href="README.es.md"><img src="https://img.shields.io/badge/Español-555555?style=for-the-badge" alt="Español"/></a>
</div>

![Geovana Grigorio — Projetos Selecionados](assets/banner.svg)

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white&style=flat-square" alt="Go">
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=flat-square" alt="Java">
  <img src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white&style=flat-square" alt="Rust">
  <img src="https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white&style=flat-square" alt="C++">
  <img src="https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white&style=flat-square" alt="C#">
  <img src="https://img.shields.io/badge/Ruby-CC342D?logo=ruby&logoColor=white&style=flat-square" alt="Ruby">
</p>

Um índice curado do meu trabalho open-source — **APIs** com pegada de produção, **web apps & dashboards**, **ferramentas CLI** e **bibliotecas**, cobrindo oito linguagens e seus ecossistemas. Todo projeto vem com testes, um README documentado e (quando aplicável) CI verde.

> 👋 Sou desenvolvedora full-stack focada em backend, APIs limpas e serviços orientados a dados. Cada item abaixo linka para seu próprio repositório.

> 🔗 **Veja tudo junto no meu portfólio:** **[portfolio-sandy-rho-84.vercel.app](https://portfolio-sandy-rho-84.vercel.app)**

---

## 🔌 Backend & APIs

| Projeto | O que faz | Stack | Testes |
|---|---|---|:--:|
| **[collections-api](https://github.com/geoggrigori/collections-api)** | API de automação de cobrança/AR para distribuidoras — pagamentos, ETL em background job e matching de remessas com LLM | `Rails` · `PostgreSQL` | — |
| **[ratewise-api](https://github.com/geoggrigori/ratewise-api)** | Middleware de rate limiting (token bucket) de nível produção para APIs Express | `TypeScript` · `Express` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/ratewise-api/ci.yml?branch=main&style=flat-square&label=) |
| **[ttlcache](https://github.com/geoggrigori/ttlcache)** | Cache chave-valor em memória, thread-safe, com TTL por chave, exposto via HTTP | `Go` · `net/http` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/ttlcache/ci.yml?branch=main&style=flat-square&label=) |
| **[library-api](https://github.com/geoggrigori/library-api)** | API REST Spring Boot com JPA, H2, validação e fluxo de empréstimo/devolução | `Java` · `Spring Boot` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/library-api/ci.yml?branch=main&style=flat-square&label=) |
| **[tasks-api-dotnet](https://github.com/geoggrigori/tasks-api-dotnet)** | Minimal API .NET limpa, com EF Core, validação, Swagger e testes de integração | `C#` · `.NET` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/tasks-api-dotnet/ci.yml?branch=main&style=flat-square&label=) |
| **[linkforge-api](https://github.com/geoggrigori/linkforge-api)** | Encurtador de URL & API de analytics, com JWT, rate limiting, cache e Docker | `FastAPI` · `Docker` | — |

## 🖥️ Web Apps & Dashboards

| Projeto | O que faz | Stack | |
|---|---|---|:--:|
| **[gamematch](https://github.com/geoggrigori/gamematch)** | App de matchmaking mobile-first para gamers — swipe, match e chat | `React` · `Supabase` · `Capacitor` | |
| **[collections-dashboard](https://github.com/geoggrigori/collections-dashboard)** | Dashboard de cobrança/AR — front-end da Collections API | `Next.js` · `React` | |
| **[revenue-analytics](https://github.com/geoggrigori/revenue-analytics)** | Dashboard de analytics de vendas — KPIs, gráficos SVG, breakdown por canal | `Next.js` · `TypeScript` | |
| **[pulse-dashboard](https://github.com/geoggrigori/pulse-dashboard)** | Dashboard de métricas em tempo real — streaming via WebSocket, gráficos SVG feitos à mão | `React` · `WebSocket` | |
| **[ar-copilot](https://github.com/geoggrigori/ar-copilot)** | Redator de e-mail de cobrança com LLM, para faturas em atraso | `Next.js` · `LLM` | |
| **[docchat-ai](https://github.com/geoggrigori/docchat-ai)** | App de RAG: converse com seus documentos — recuperação BM25 + respostas citadas em streaming | `Next.js` · `RAG` | |
| **[marknote](https://github.com/geoggrigori/marknote)** | App de notas Markdown rápido, com preview ao vivo, busca e modo escuro | `React` · `Vite` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/marknote/ci.yml?branch=main&style=flat-square&label=) |

## 🛠️ CLI & Ferramentas de Dados

| Projeto | O que faz | Stack | Testes |
|---|---|---|:--:|
| **[envguard](https://github.com/geoggrigori/envguard)** | Valida variáveis de ambiente contra um schema TOML declarativo (CI-friendly) | `Python` · `zero-deps` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/envguard/ci.yml?branch=main&style=flat-square&label=) |
| **[exprcalc](https://github.com/geoggrigori/exprcalc)** | Avaliador de expressões aritméticas: lexer + parser recursivo-descendente + REPL | `Rust` · `zero-deps` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/exprcalc/ci.yml?branch=main&style=flat-square&label=) |
| **[insight-pipeline](https://github.com/geoggrigori/insight-pipeline)** | Pipeline de dados: ingestão CSV/API, agregação, detecção de tendências e relatórios automáticos | `Python` · `pandas` | — |

## 📦 Bibliotecas & Estruturas de Dados

| Projeto | O que faz | Stack | Testes |
|---|---|---|:--:|
| **[lru-cache-cpp](https://github.com/geoggrigori/lru-cache-cpp)** | Cache LRU O(1), header-only e templated, para C++17 moderno | `C++17` · `CMake` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/lru-cache-cpp/ci.yml?branch=main&style=flat-square&label=) |

---

## 🧰 Tecnologias usadas nesses projetos

**Linguagens:** TypeScript · JavaScript · Python · Go · Java · Rust · C++ · C# · Ruby
**Backend:** Node/Express · FastAPI · Spring Boot · ASP.NET Minimal API · Rails · net/http
**Frontend:** React · Next.js · Vite · Tailwind CSS
**Dados & infra:** PostgreSQL · H2 · EF Core · JPA · Supabase · Docker · pandas · WebSocket
**Qualidade:** Vitest · pytest · JUnit · xUnit · CTest · `go test -race` · GitHub Actions CI

## 📫 Contato

- **Portfólio:** [portfolio-sandy-rho-84.vercel.app](https://portfolio-sandy-rho-84.vercel.app)
- **GitHub:** [@geoggrigori](https://github.com/geoggrigori)
- **LinkedIn:** [in/geoggrigori](https://linkedin.com/in/geoggrigori)
