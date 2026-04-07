<p align="center">
  <img src="https://raw.githubusercontent.com/Trade360Lab/Trade360Lab/main/frontend/public/Logo.png" width="400"/>
</p>

<h1 align="center">Trading research platform</h1>

<p align="center">
  <a href="https://t360lab.tech">Главная</a> |
  <a href="https://t360lab.tech/">Документация</a> |
  <a href="https://t.me/trading360l">Telegram</a> |
  <a href="https://github.com/Trade360Lab/Trade360Lab">Основной репозиторий</a>
</p>

<h2 align="center">Архитектура</h2>

```mermaid
flowchart LR
    U[User / UI] --> F[Frontend]

    F --> J[Java API]

    J --> P[Python Engine]
    J --> D[(PostgreSQL)]

    P --> D

    subgraph Backend
        J
        P
        D
    end
```

<h2 align="center">Стек технологий</h2>

<table align="center">
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>CI / DevOps</b></td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/Next.js-16-000000?logo=next.js&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/React-18-20232A?logo=react&logoColor=61DAFB" /><br/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Radix_UI-161618?logo=radixui&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Recharts-22C55E?logo=chartdotjs&logoColor=white" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Spring_Boot-3-6DB33F?logo=springboot&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?logo=postgresql&logoColor=white" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" /><br/>
      <img src="https://github.com/Trade360Lab/Trade360Lab/actions/workflows/ci.yml/badge.svg" />
    </td>
  </tr>
</table>

<h2 align="center">Roadmap</h2>

* [x] Data pipeline
* [x] Strategy contract
* [x] Backtesting engine
* [x] Java orchestration
* [ ] Optimization engine
* [ ] Paper trading
* [ ] ML / AI layer

---

<p align="center">
  Build. Test. Explore. <br/>
  GNU GPL v3 License
</p>
