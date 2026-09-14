# BUILD_CODEX — Riftsteel Arena

**Top success pick** for VR-CLONE-MASTER. Detailed agent prompt to ship an original physics-melee MVP across Meta Quest (App Lab), SideQuest, Steam Frame, and optional PC VR OpenXR / Steam.

**Working title:** Riftsteel Arena  
**Genre inspiration (internal docs only):** Blade & Sorcery: Nomad–class physics melee  
**Engine:** Godot 4.x + OpenXR (preferred)

---

## Mission

Build a **playable physics melee sandbox + wave mode** with **full UI**, comfort options, and store-ready packaging notes. Original IP only — no trademarks, asset rips, or lookalike logos.

---

## Platforms

| Platform | Path | Notes |
|----------|------|-------|
| **Meta Quest** | App Lab | Android ARM64, Vulkan, OpenXR; Touch interaction profile |
| **SideQuest** | Sideload APK | Same Quest build; SideQuest listing copy uses **Riftsteel Arena** only |
| **Steam Frame** | OpenXR / Android depot | Prefer OpenXR; Frame controller profile or Touch remap; no hand-tracking-only UX |
| **PC VR (optional)** | Steam / OpenXR | Same project; desktop OpenXR export |

Never require Meta-only plugins that break Steam Frame.

---

## MVP gameplay

### Arena

- One mid-size stone-and-steel arena (circular + side alcoves for weapon racks)
- Spawn volumes for enemies; kill floor / reset bounds
- Lighting: dramatic emissive accents, Quest-safe fill

### Physics melee

- Grabable weapons: **1H sword**, **2H axe**, **spear**, **shield**
- Two-hand pose when second grip engages
- Damage ≈ relative velocity × edge alignment factor (tunable)
- Simple dismember / disable limb stubs (optional visual; functional limb HP OK)

### Enemies (3 types)

1. **Grunt** — light, rushes, 1H weapon
2. **Shieldbearer** — blocks frontal hits; flankable
3. **Brute** — slow, high HP, telegraphed heavy swings

### Modes

1. **Sandbox** — free spawn weapons + enemies from wrist radial
2. **Wave Survival** — 5 waves, scaling counts, short rest between waves

### Comfort (mandatory)

- Teleport + snap-turn default
- Smooth locomotion + smooth turn opt-in
- Seated mode + player height calibration
- Tunnel vignette on move
- Dominant hand setting

---

## Full UI

- [ ] Main menu: Sandbox / Waves / Arsenal / Settings / Credits
- [ ] Arsenal rack world UI + spawn buttons
- [ ] Wrist inventory: HP, wave #, quick comfort, leave
- [ ] Health bar + damage vignette + hit direction indicator
- [ ] Wave banner / sandbox radial menu
- [ ] Pause sheet: resume / restart / settings / quit
- [ ] Settings: locomotion, vignette strength, physics quality, seated, language stub
- [ ] Credits: original IP notice (no third-party game names)

---

## Technical acceptance

- [ ] Stable ≥72 Hz on Quest 3–class target for sandbox with ≤6 enemies (document if not)
- [ ] Controllers: OpenXR; Frame-safe bindings
- [ ] No hand-tracking-only critical path
- [ ] Export presets documented for Quest APK + desktop
- [ ] Zero trademarked strings in UI

---

## Packaging checklist

1. SideQuest: screenshots, short + long description, comfort rating, price stub
2. App Lab: data safety, age rating notes, trailer script outline
3. Steam Frame: Verified bar awareness (resolution / fps); controller glyphs
4. Secrets: never commit keystores — use CI env vars

---

## Out of scope

Online multiplayer, UGC map workshop, full RPG loot grind, photo-real humans, licensed music.

## Assets

Use [`IMAGE_PROMPTS.md`](IMAGE_PROMPTS.md) and [`PROMPTS_3D.md`](PROMPTS_3D.md). Title folder: [`../titles/riftsteel-arena/`](../titles/riftsteel-arena/).
