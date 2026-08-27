<!-- ══════════════════════════ PORTADA ══════════════════════════ -->
<div align="center">
  <img src="assets/title-banner.svg" width="100%" alt="Geovana Grigorio"/>
</div>

<br/>

<!-- ══════════════════════ IDIOMAS / LANGUAGES ══════════════════════ -->
<div align="center">
<a href="README.md"><img src="https://img.shields.io/badge/Português-555555?style=for-the-badge" alt="Português"/></a>
<a href="README.en.md"><img src="https://img.shields.io/badge/English-555555?style=for-the-badge" alt="English"/></a>
<a href="README.es.md"><img src="https://img.shields.io/badge/Español-1987F0?style=for-the-badge" alt="Español"/></a>
</div>

<br/>

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

Un índice curado de mi trabajo open-source — **APIs** de nivel producción, **web apps & dashboards**, **herramientas CLI** y **bibliotecas**, cubriendo ocho lenguajes y sus ecosistemas. Cada proyecto incluye pruebas, un README documentado y (cuando aplica) CI en verde.

> 👋 Soy desarrolladora full-stack enfocada en backend, APIs limpias y servicios orientados a datos. Cada entrada abajo enlaza a su propio repositorio.

> 🔗 **Mira todo junto en mi portafolio:** **[geoggrigori.vercel.app](https://geoggrigori.vercel.app)**

---

## 🔌 Backend & APIs

| Proyecto | Qué hace | Stack | Pruebas |
|---|---|---|:--:|
| **[collections-api](https://github.com/geoggrigori/collections-api)** | API de automatización de cobranza/AR para distribuidoras — pagos, ETL en background job y matching de remesas con LLM | `Rails` · `PostgreSQL` | — |
| **[ratewise-api](https://github.com/geoggrigori/ratewise-api)** | Middleware de rate limiting (token bucket) de nivel producción para APIs Express | `TypeScript` · `Express` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/ratewise-api/ci.yml?branch=main&style=flat-square&label=) |
| **[ttlcache](https://github.com/geoggrigori/ttlcache)** | Caché clave-valor en memoria, thread-safe, con TTL por clave, expuesto vía HTTP | `Go` · `net/http` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/ttlcache/ci.yml?branch=main&style=flat-square&label=) |
| **[library-api](https://github.com/geoggrigori/library-api)** | API REST Spring Boot con JPA, H2, validación y flujo de préstamo/devolución | `Java` · `Spring Boot` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/library-api/ci.yml?branch=main&style=flat-square&label=) |
| **[tasks-api-dotnet](https://github.com/geoggrigori/tasks-api-dotnet)** | Minimal API .NET limpia, con EF Core, validación, Swagger y pruebas de integración | `C#` · `.NET` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/tasks-api-dotnet/ci.yml?branch=main&style=flat-square&label=) |
| **[linkforge-api](https://github.com/geoggrigori/linkforge-api)** | Acortador de URL & API de analytics, con JWT, rate limiting, caché y Docker | `FastAPI` · `Docker` | — |

## 🖥️ Web Apps & Dashboards

| Proyecto | Qué hace | Stack | |
|---|---|---|:--:|
| **[gamematch](https://github.com/geoggrigori/gamematch)** | App de matchmaking mobile-first para gamers — swipe, match y chat | `React` · `Supabase` · `Capacitor` | |
| **[collections-dashboard](https://github.com/geoggrigori/collections-dashboard)** | Dashboard de cobranza/AR — frontend de la Collections API | `Next.js` · `React` | |
| **[revenue-analytics](https://github.com/geoggrigori/revenue-analytics)** | Dashboard de analytics de ventas — KPIs, gráficos SVG, desglose por canal | `Next.js` · `TypeScript` | |
| **[pulse-dashboard](https://github.com/geoggrigori/pulse-dashboard)** | Dashboard de métricas en tiempo real — streaming vía WebSocket, gráficos SVG hechos a mano | `React` · `WebSocket` | |
| **[ar-copilot](https://github.com/geoggrigori/ar-copilot)** | Redactor de emails de cobranza con LLM, para facturas vencidas | `Next.js` · `LLM` | |
| **[docchat-ai](https://github.com/geoggrigori/docchat-ai)** | App de RAG: chatea con tus documentos — recuperación BM25 + respuestas citadas en streaming | `Next.js` · `RAG` | |
| **[marknote](https://github.com/geoggrigori/marknote)** | App de notas Markdown rápida, con preview en vivo, búsqueda y modo oscuro | `React` · `Vite` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/marknote/ci.yml?branch=main&style=flat-square&label=) |

## 🛠️ CLI & Herramientas de Datos

| Proyecto | Qué hace | Stack | Pruebas |
|---|---|---|:--:|
| **[envguard](https://github.com/geoggrigori/envguard)** | Valida variables de entorno contra un schema TOML declarativo (CI-friendly) | `Python` · `zero-deps` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/envguard/ci.yml?branch=main&style=flat-square&label=) |
| **[exprcalc](https://github.com/geoggrigori/exprcalc)** | Evaluador de expresiones aritméticas: lexer + parser recursivo-descendente + REPL | `Rust` · `zero-deps` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/exprcalc/ci.yml?branch=main&style=flat-square&label=) |
| **[insight-pipeline](https://github.com/geoggrigori/insight-pipeline)** | Pipeline de datos: ingesta CSV/API, agregación, detección de tendencias y reportes automáticos | `Python` · `pandas` | — |

## 📦 Bibliotecas & Estructuras de Datos

| Proyecto | Qué hace | Stack | Pruebas |
|---|---|---|:--:|
| **[lru-cache-cpp](https://github.com/geoggrigori/lru-cache-cpp)** | Caché LRU O(1), header-only y templated, para C++17 moderno | `C++17` · `CMake` | ![CI](https://img.shields.io/github/actions/workflow/status/geoggrigori/lru-cache-cpp/ci.yml?branch=main&style=flat-square&label=) |

---

## 🧰 Tecnología en estos proyectos

**Lenguajes:** TypeScript · JavaScript · Python · Go · Java · Rust · C++ · C# · Ruby
**Backend:** Node/Express · FastAPI · Spring Boot · ASP.NET Minimal API · Rails · net/http
**Frontend:** React · Next.js · Vite · Tailwind CSS
**Datos e infra:** PostgreSQL · H2 · EF Core · JPA · Supabase · Docker · pandas · WebSocket
**Calidad:** Vitest · pytest · JUnit · xUnit · CTest · `go test -race` · GitHub Actions CI

## 📫 Contacto

- **Portafolio:** [geoggrigori.vercel.app](https://geoggrigori.vercel.app)
- **GitHub:** [@geoggrigori](https://github.com/geoggrigori)
- **LinkedIn:** [in/geoggrigori](https://linkedin.com/in/geoggrigori)
