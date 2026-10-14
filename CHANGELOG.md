# 📋 SrTowny Changelog

All notable architectural updates and feature additions to **SrTowny** are documented in this file.

---

## [1.1.0] - 2026-10-14

### 🚀 Added
- **SrOgretici (Interactive Onboarding Engine):**
  - Integrated multi-stage guided journey with real-time Adventure BossBar tracking.
  - Multi-path municipal progression: Town discovery, founding/joining, financial routines, claim milestone audits, and routine hooks.
  - Anti-abuse verification: Guaranteed single-redemption validation and skip controls.
  - Fully isolated modular architecture (`AbstractSrTownyModule`) with hot-reloading and automatic state cleanup.
- **SrKomutan 2.0 (Military Engine Overhaul):**
  - Expanded multi-tier commander progression system.
  - Dynamic tactical combat VFX: Custom status effect tracking particles, area-of-effect visual rings, and ambient aura effects engineered for PvP clarity.
  - Subtle attribute scaling: Nuanced movement velocity and physical scale adjustments tuned for competitive balance.
  - Metric compact currency formatting for scoreboards, announcements, and HUDs.
- **Town Security & Teleport Safeguards:**
  - Automated asynchronous memory-safe chunk trap auditor preventing high-elevation void/pit hazards.
  - Arrival invulnerability guard preventing spawn camping and ambush griefing.

### 🔄 Changed
- Renamed and decoupled the onboarding system to **SrOgretici** with isolated module storage.
- Standardized UI divider formatting across all interfaces to smooth, unbroken solid lines.
- Enforced unified SmallCaps and warm gradient typography across announcements and menus.

### 🛡️ Security & Performance
- Resolved event listener duplication in core subsystems.
- Implemented automated task and listener dereferencing on module lifecycle transitions.
- Hardened siege combat evasion guards during blackout windows.
