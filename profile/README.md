<p align="center">
  <img src="https://raw.githubusercontent.com/Trade360Lab/Trade360Lab/main/frontend/public/Logo.png" width="550"/>
</p>

<h1 align="center">Trading research platform</h1>

<p align="center">
  <a href="https://t360lab.tech">Главная</a> |
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

<h2 align="center">Roadmap of Trade360Lab</h2>

<div align="center">

<table width="100%">
<tr>

<td valign="top" width="50%" align="center">

### Core Engine

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Data pipeline</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Strategy contract</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Backtesting engine</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Java orchestration</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Optimization engine</td><td><img src="https://img.shields.io/badge/status-in_progress-yellow"></td></tr>
<tr><td>Event-driven engine</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

<td valign="top" width="50%" align="center">

### Trading

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Paper trading</td><td><img src="https://img.shields.io/badge/status-in_progress-yellow"></td></tr>
<tr><td>Live trading</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Order management system</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Risk management</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Position sizing</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

</tr>

<tr>

<td valign="top" align="center">

### ML / AI

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Feature engineering</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Model training</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Online inference</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Meta-labeling</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Reinforcement learning</td><td><img src="https://img.shields.io/badge/status-future-lightgrey"></td></tr>
</table>

</td>

<td valign="top" align="center">

### Analytics

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Equity curve</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Metrics (Sharpe, Sortino)</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Drawdown analysis</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Trade logs</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

</tr>
</table>

</div>

---

<p align="center">
  Build. Test. Explore. <br/>
  GNU GPL v3 License
</p>
