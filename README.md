<div align="center">

# imlast999

### Software Engineer & Quantitative Systems Architect

> **Research • Validate • Execute • Improve**

Building production-grade financial software where every decision is backed by empirical research, systematic risk modeling, and rigorous automated verification.

<br>

<p align="center">
  <a href="https://github.com/imlast999/LastEdge">
    <img src="https://img.shields.io/badge/🚀%20Ecosystem-LastEdge%20Platform-2ea043?style=for-the-badge"/>
  </a>
  <a href="https://github.com/imlast999/lastedge-trading-engine/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/imlast999/lastedge-trading-engine/ci.yml?branch=main&label=Trading%20Engine%20CI&style=for-the-badge&logo=githubactions&logoColor=white&color=2ea043"/>
  </a>
</p>

<br>

![Python](https://img.shields.io/badge/Python_3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MetaTrader5](https://img.shields.io/badge/MetaTrader_5-0055A4?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite_WAL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

# 👋 About Me

I am a software engineer focused on building **high-reliability quantitative trading systems**, algorithmic execution engines, and financial technology infrastructure. 

My work centers around **LastEdge**, an institutional-grade algorithmic trading platform that decouples quantitative research, low-latency order routing, and real-time operational telemetry into dedicated micro-architectures.

Rather than chasing complexity for its own sake, I build deterministic systems engineered for 24/7 uptime, reproducible statistical alpha, and strict capital preservation.

### Core Focus Areas:
- ⚡ **Algorithmic Execution & Order Routing**: Sub-second execution pipelines interfacing with MetaTrader 5 with millisecond latency and signed slippage tracking.
- 🛡️ **Quantitative Risk Architecture**: Multi-tier Risk Engines featuring dynamic lot sizing, broker exposure safeguards, and equity circuit breakers.
- 🔬 **Systematic Strategy Research**: Walk-forward analysis (WFA), Monte Carlo stress simulations, and automated promotion pipelines.
- 📱 **Operational Control Planes**: Real-time cross-platform telemetry dashboards (React Native / Expo) and automated notification dispatchers.

---

# 🏛️ The LastEdge Ecosystem

**LastEdge** is structured as an ecosystem of decoupled, specialized repositories operating in harmony:

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>⚡ <a href="https://github.com/imlast999/lastedge-trading-engine">Trading Engine</a></h3>
      <p><b>Institutional Execution & Risk Core</b></p>
      <ul>
        <li>Sub-second order routing to MetaTrader 5</li>
        <li><b>Risk Engine v2</b>: Dynamic sizing, daily drawdown circuit breakers, and broker-compliant margin checks (FXLiveCapital 10% safeguard)</li>
        <li>100% Autonomous execution mode with dynamic ATR trailing stops & breakeven protection</li>
        <li>Complete CI matrix on Python 3.10, 3.11, 3.12 (110 automated tests passing)</li>
      </ul>
      <a href="https://github.com/imlast999/lastedge-trading-engine">
        <img src="https://img.shields.io/badge/Explore-Trading%20Engine-2ea043?style=flat-square&logo=github"/>
      </a>
    </td>
    <td width="33%" valign="top">
      <h3>🧪 <a href="https://github.com/imlast999/lastedge-strategy-lab">Strategy Lab</a></h3>
      <p><b>Quantitative Research & Validation Lab</b></p>
      <ul>
        <li>Walk-Forward Analysis (WFA) to eliminate curve-fitting and data-snooping bias</li>
        <li>Monte Carlo stress testing (1,000+ permutations per strategy regime)</li>
        <li><b>Exit Research Suite</b>: Optimization for partial exits, trailing stop curves, and risk/reward ratios</li>
        <li>Automated strategy promotion pipelines with verifiable cryptographic manifests</li>
      </ul>
      <a href="https://github.com/imlast999/lastedge-strategy-lab">
        <img src="https://img.shields.io/badge/Explore-Strategy%20Lab-2ea043?style=flat-square&logo=github"/>
      </a>
    </td>
    <td width="33%" valign="top">
      <h3>📱 <a href="https://github.com/imlast999/lastedge-app">LastEdge App</a></h3>
      <p><b>Mission Control & Telemetry Suite</b></p>
      <ul>
        <li>Cross-platform mobile application built with <b>React Native</b> and <b>Expo</b> (standalone Android APK builds)</li>
        <li>Real-time Web Control Dashboard (FastAPI / Server-Sent Events / WebSockets)</li>
        <li>Multi-channel alert dispatchers via Telegram & Discord bot gateways</li>
        <li>Live position monitoring, manual signal overrides, and telemetry feeds</li>
      </ul>
      <a href="https://github.com/imlast999/lastedge-app">
        <img src="https://img.shields.io/badge/Explore-LastEdge%20App-2ea043?style=flat-square&logo=github"/>
      </a>
    </td>
  </tr>
</table>

<p align="center">
  <i>The umbrella repository coordinating system-wide orchestrations, unified CLI commands, and deployment scripts is available at <a href="https://github.com/imlast999/LastEdge"><b>imlast999/LastEdge</b></a>.</i>
</p>

---

# ⚙️ Production Highlights & Reliability

- 🟢 **24/7 Autonomous Live Trading**: Continuously deployed on a dedicated execution host managed via PM2 process orchestration with automated health watchdogs.
- 🛡️ **Capital & Margin Preservation**: Zero margin breaches or drawdown violations; active risk engine strictly enforcing capital safety rules across all market sessions.
- 📝 **Cryptographic Audit Trail**: Full trade lifecycle persisted to high-concurrency SQLite (WAL mode) with microsecond execution timestamps, slippage calculation, and telemetry logging.
- 🧪 **100% Green Test Suite**: Strict automated test coverage across Linux runners and Windows execution environments.

---

# 🛠️ Tech Stack & Tooling

<div align="left">

| Domain | Technologies & Libraries |
| :--- | :--- |
| **Quantitative & Trading** | Python 3.12+, MetaTrader 5 API, Pandas, NumPy, TA-Lib, VectorBT, Mplfinance |
| **Backend & Execution** | FastAPI, Flask, SQLite3 (WAL mode), Aiohttp, Cryptography, WebSockets, Asyncio |
| **Mobile & Frontend** | React Native, Expo, React 18, TypeScript, TailwindCSS / NativeWind |
| **Infrastructure & DevOps** | GitHub Actions (CI/CD), PM2 Process Manager, Git, Linux / Windows Server, Pytest |
| **Alerts & Integrations** | Telegram Bot API, Discord API, Cloudflare Tunnels, SSH Remote Access |

</div>

---

# 📂 Other Featured Repositories

- 🦈 **[millionaire-sharks-tg-bot](https://github.com/imlast999/millionaire-sharks-tg-bot)**: High-throughput Telegram automation bot for quantitative alert broadcasting and community analytics.
- ⚡ **[cs-arbitrage](https://github.com/imlast999/cs-arbitrage)**: Cross-market algorithmic arbitrage and liquidity spread monitoring algorithms.
- 🎓 **[grademe-portfolio](https://github.com/imlast999/grademe-portfolio)**: Rigorous algorithmic problem-solving repository with solutions validated by automated grading suites.

---

# 🔗 Connect With Me

<p align="left">
  <a href="https://x.com/imlast999">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/>
  </a>
  <a href="https://instagram.com/imlast999">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="https://youtube.com/@imlast999">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
  </a>
  <a href="https://github.com/imlast999">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

# 📊 GitHub Analytics

<p align="center">
  <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api?username=imlast999&show_icons=true&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000&count_private=true"/>
  <img height="165" src="https://github-readme-stats-five-sigma-99.vercel.app/api/top-langs/?username=imlast999&layout=compact&theme=tokyonight&title_color=2ea043&icon_color=2ea043&hide_border=true&bg_color=00000000"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=imlast999&bg_color=00000000&color=2ea043&line=2ea043&point=c9d1d9&area=true&hide_border=true"/>
</p>

---

<div align="center">

### Research • Validate • Execute • Improve

⭐ *Building **LastEdge**, one deterministic system at a time.*

<br>

<a href="https://grademe.fr/app/user/2b062535-a21b-46bc-b3c8-042c83241752">
  <img src="https://grademe.fr/api/cards/b0d7689d-6a64-46fe-8c6f-5a05bb91a85b.svg" alt="Grademe profile card for @imlast999" width="1200" height="420" style="max-width: 100%; height: auto;">
</a>

</div>
