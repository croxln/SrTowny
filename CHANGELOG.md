# 📋 SrTowny Changelog

All notable architectural updates and feature additions to **SrTowny** are documented in this file.

---

## [1.1.0] - 2026-10-14

### 🚀 Added
- **SrOgretici (Onboarding Engine Module):**
  - Integrated 7-stage interactive beginner tutorial (`/ogretici`, `/srogretici`, `/rehber`).
  - Real-time Adventure BossBar tracking with step progress and sound/particle celebrations.
  - Multi-path town progression: Town creation, specialization selection (mine vein prospecting), town bank deposit checks, claim verification, town hall construction, and daily routine hooks (`/rankup`, `/gunlukodul`).
  - Exploit prevention: One-time reward verification, skip tracking, and zero rewards on skipped journeys.
  - Dedicated isolated module architecture (`AbstractSrTownyModule`) with hot-reloading and automatic BossBar cleanup.
- **SrKomutan 2.0 (Rise of Kingdoms Overhaul):**
  - Expanded 6-Tier Commander Matrix (Sıradan, Sıradışı, Ender, Destansı, Efsanevi, Mitik).
  - Secret Mythic Commander: **Ressam (???)** with server-wide lightning strike sound effects and 5-second bossbar broadcast upon unboxing.
  - League of Legends inspired dynamic combat VFX:
    - Darius hemorrhage bleed mechanic: Stacking orbital blood particles around targets with increasing severity.
    - Veigar event horizon stun cage particle circle.
    - Vel'Koz disintegration beam particle effect.
    - Rotating square aura ambient particle effects engineered for competitive PvP clarity.
  - Dynamic subtle player scale attributes: Light speed buffs/size adjustments for nimble commanders, subtle scale increase and speed adjustments for heavy tanks.
  - Compact large currency formatter (`K`, `M`, `B`) for scoreboards and bossbars.
- **Town Safety & Teleport Protections:**
  - Automated asynchronous memory-safe chunk trap auditor (`TownSpawnTrapAuditTask`) protecting against elevated void/hole traps.
  - Post-teleport invulnerability guard (`TownTeleportProtectionListener`) preventing spawn-kill camping.

### 🔄 Changed
- Renamed onboarding system to **SrOgretici** with isolated storage in `plugins/SrTowny/modules/SrOgretici/`.
- Standardized UI divider formatting to solid strikethrough aesthetics (`<st><dark_gray>                        </dark_gray></st>`).
- Enforced strict SmallCaps and warm gradient typography across all module GUI menus and announcements.

### 🛡️ Security & Performance
- Fixed duplicate event listener registration in SrTowny core.
- Added automatic listener and task dereferencing on module disable/reload.
- Prevented siege war evading during scheduled blackout windows.
