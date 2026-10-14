<div align="center">

# 🏰 SrTowny
### Next-Gen Server Core, Advanced Towny & SiegeWar Architecture Engine

[![Java 21](https://img.shields.io/badge/Java-21_LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![PaperMC](https://img.shields.io/badge/PaperMC-1.21.x-1F8CEB?style=for-the-badge&logo=minecraft&logoColor=white)](https://papermc.io/)
[![Version](https://img.shields.io/badge/Version-1.1.0-38BDF8?style=for-the-badge)](https://github.com/croxln/SrTowny)
[![Status](https://img.shields.io/badge/Status-🟢_Active_Production-4ADE80?style=for-the-badge)](https://github.com/croxln/SrTowny)
[![Stars](https://img.shields.io/github/stars/croxln/SrTowny?style=for-the-badge&color=FACC15&logo=github)](https://github.com/croxln/SrTowny/stargazers)
[![License](https://img.shields.io/badge/License-Proprietary-EF4444?style=for-the-badge)](https://github.com/croxln/SrTowny)

<p align="center">
  <b>SrTowny</b> is an enterprise fork of Towny Advanced and SiegeWar, engineered specifically for high-concurrency competitive multiplayer servers.<br>
  Featuring thread-safe nation warfare, Hall of Fame NPC integrations, modern tax calculation models, and seamless plugin interoperability.
</p>

</div>

---

### 🌟 Architectural Pillars

- **⚔️ Hardened SiegeWar Engine:** Re-architected combat zones with exploit-free banner mechanics, anti-farm cooldowns, and grief-protected war sites.
- **🎖️ SrKomutan (Rise of Kingdoms Military Engine):** 6-tier matrix (Common to Mythic), secret commander mechanics, League of Legends inspired particle warfare (hemorrhage stacking, stun cages, rays), and subtle player scale dynamics.
- **🧭 SrOgretici (Interactive Onboarding Engine):** 7-step guided journey, real-time Adventure BossBar tracking, automated town progression verification, and isolated module lifecycle management.
- **🛡️ Town Safety & Anti-Trap Systems:** Asynchronous memory-safe chunk trap auditor and post-teleport invulnerability shields preventing spawn exploitation.
- **🏆 Hall of Fame Integration:** Citizens interact with monthly Hall of Fame NPCs featuring async debounced right-click listeners, ranking boards, and prestige rewards.
- **🎨 Modern MiniMessage Aesthetic:** 100% legacy color code purged. Formatted exclusively with Adventure MiniMessage, rich hex palettes, and smooth solid dividers.
- **⚡ High-Throughput Database Operations:** Async query processing for town blocks, resident data, and national treaties.

---

### 📦 Modular Engine Architecture

SrTowny operates on an isolated plugin-in-plugin module architecture (`AbstractSrTownyModule`), ensuring hot-reloadability, dedicated configurations, and clean resource cleanup:

| Module | Identifier | Description | Status |
| :--- | :--- | :--- | :--- |
| **SrOgretici** | `srogretici` | 7-step interactive town onboarding journey with live BossBar tracking | `ACTIVE` |
| **SrKomutan** | `srkomutan` | RoK-inspired commander collection, talent progression & particle combat | `ACTIVE` |
| **Kasaba Baskını** | `kasaba_baskini` | PvE raid wave encounters with custom AI pathfinders and boss mechanics | `ACTIVE` |
| **Kasaba Events** | `kasaba_events` | Dynamic seasonal and server-wide town competitive events | `ACTIVE` |
| **SrKervan** | `srkervan` | Scheduled high-stakes cross-server caravan escort & plunder gameplay | `ACTIVE` |
| **Town Governor** | `governor` | Town succession inheritance, emergency tax calls & progressive taxation | `ACTIVE` |
| **Hall of Fame** | `hall_of_fame` | Monthly prestige ranking monuments and NPC interactions | `ACTIVE` |
| **Towny Flight** | `flight` | Claim-bounded tactical flight permissions and combat blackout enforcement | `ACTIVE` |

---

### 📈 Repository Star History

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=croxln/SrTowny&type=Date&theme=dark)](https://star-history.com/#croxln/SrTowny&Date)

</div>

---

> [!IMPORTANT]
> **Source Code Notice:** This repository serves as a public architectural showcase, changelog, and issue tracker for the **SrProjects** suite. The core source code is proprietary and closed-source.

<div align="center">
<sub>Engineered by <b>-Serhat (croxln)</b> • Part of the SrProjects Suite</sub>
</div>
