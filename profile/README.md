<p align="center">
  <img src="https://raw.githubusercontent.com/Trade360Lab/Trade360Lab/main/frontend/public/Logo.png" width="550"/>
</p>

<h1 align="center">Quantitative trading lab for building and testing strategies</h1>

<p align="center">
  <a href="https://t360lab.tech">Главная</a> |
  <a href="https://t360lab.tech/docs">Документация</a> |
  <a href="https://t.me/trading360l">Telegram</a> 
</p>

<p align="center">
<a href="https://github.com/Trade360Lab/Trade360Lab">Основной репозиторий</a> |
<a href="https://github.com/Trade360Lab/Trade360Lab-Strategies.git">Стратегии и индикаторы</a>
</p>

<p align="center">

</p>

```mermaid
flowchart LR
    A["Trade360Lab<br/>Quantitative Trading Lab"]

    A --> B["Landing<br/>Website"]
    A --> C["GitHub<br/>Organization"]

    C --> D["Main Repo<br/>Trade360Lab"]
    C --> E["Strategies Repo<br/>Trade360Lab-Strategies"]
    C --> F["Bots / Analyzers"]

    F --> G["BTC Analyzer Bot"]
    F --> H["Other Bots"]
    F --> I["Future Bots"]

    D --> J["Platform Core"]
    E --> K["Strategies & Indicators"]
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

### Platform Core

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Monorepo structure</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Docker Compose full stack</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Java API control plane</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Python execution engine</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>PostgreSQL persistence</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Readiness dashboard</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Event-driven engine</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

<td valign="top" width="50%" align="center">

### Data & Execution

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Market data import</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Binance candles parser</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Dataset snapshots</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Dataset quality reports</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Queued execution jobs</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Run snapshots / reproducibility</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Optimization engine</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

</tr>

<tr>

<td valign="top" align="center">

### Strategies & Backtesting

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Strategy upload</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Strategy validation</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Strategy registry</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Strategy versioning</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Strategy templates</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Parameter presets</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Backtest execution</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
</table>

</td>

<td valign="top" align="center">

### Analytics & Reports

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Run metrics</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Equity curve artifacts</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Trades export</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Run report JSON</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Compare runs UI</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Diagnostics bundle</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Advanced portfolio analytics</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

</tr>

<tr>

<td valign="top" align="center">

### Trading

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>Paper trading sessions</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Paper orders / fills</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Paper positions / balance</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Live trading foundation</td><td><img src="https://img.shields.io/badge/status-in_progress-yellow"></td></tr>
<tr><td>Live risk gates</td><td><img src="https://img.shields.io/badge/status-in_progress-yellow"></td></tr>
<tr><td>Kill switch / circuit breaker</td><td><img src="https://img.shields.io/badge/status-in_progress-yellow"></td></tr>
<tr><td>Production live trading</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
</table>

</td>

<td valign="top" align="center">

### Security, Ops & AI

<table width="100%" style="font-size:12px;">
<tr><th>Feature</th><th>Status</th></tr>
<tr><td>JWT authentication</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>User-scoped resources</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Internal API secret protection</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>CI quality gates</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>Release / safety workflows</td><td><img src="https://img.shields.io/badge/status-done-brightgreen"></td></tr>
<tr><td>ML feature engineering</td><td><img src="https://img.shields.io/badge/status-planned-blue"></td></tr>
<tr><td>Model training / inference</td><td><img src="https://img.shields.io/badge/status-future-lightgrey"></td></tr>
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
