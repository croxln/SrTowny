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
  <b>SrTowny</b> is an enterprise fork of Towny Advanced and SiegeWar, engineered specifically for high-concurrency competitive multiplayer networks.<br>
  Featuring thread-safe nation warfare, specialized military command structures, modern tax calculation models, and seamless plugin interoperability.
</p>

</div>

---

### 🌟 Core Architectural Pillars

- **⚔️ Hardened SiegeWar Engine:** Re-architected combat zones with anti-exploit banner mechanics, anti-farm cooldowns, and grief-protected war sites.
- **🎖️ SrKomutan Military Engine:** Multi-tiered commander progression, tactical combat synergies, dynamic visual effects, and customized player attribute scaling.
- **🧭 SrOgretici Onboarding Engine:** Milestone-based interactive progression system with real-time Adventure BossBar tracking and lifecycle isolation.
- **🛡️ Municipal Security & Anti-Trap Safeguards:** Asynchronous spatial integrity verifiers and post-teleport protection layers preventing spawn exploitation.
- **🏛️ Town Governance & Progression:** Automated progressive taxation models, succession protocols, and specialized municipal structures.
- **🏆 Hall of Fame Integration:** Competitive monuments, async-debounced NPC interactions, and monthly prestige recognition.
- **🎨 Modern MiniMessage Aesthetic:** 100% legacy color code purged. Formatted exclusively with Adventure MiniMessage, rich hex gradients, and smooth solid dividers.
- **⚡ High-Throughput Database Operations:** Async query processing for town blocks, resident data, and national treaties.

---

### 📦 Modular Engine Architecture

SrTowny operates on an isolated plugin-in-plugin module architecture (`AbstractSrTownyModule`), ensuring hot-reloadability, dedicated configurations, and clean resource cleanup:

| Module | Identifier | Description | Status |
| :--- | :--- | :--- | :--- |
| **SrOgretici** | `srogretici` | Milestone-based interactive player onboarding journey with live HUD tracking | `ACTIVE` |
| **SrKomutan** | `srkomutan` | Multi-tier tactical commander collection, talent progression & combat visuals | `ACTIVE` |
| **Kasaba Baskını** | `kasaba_baskini` | PvE raid wave encounters with custom AI pathfinders and boss mechanics | `ACTIVE` |
| **Kasaba Events** | `kasaba_events` | Dynamic seasonal and server-wide municipal competitive events | `ACTIVE` |
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
