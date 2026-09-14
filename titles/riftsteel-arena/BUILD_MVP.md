# BUILD_MVP — Riftsteel Arena

You are a VR game coding agent. Build a **playable MVP** for **Riftsteel Arena** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: Blade & Sorcery: Nomad (genre inspiration only — physics melee). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Physics melee sandbox — grab rift-forged steel, duel wave enemies or free-roam the arena, and master two-hand grips.

## Implement these mechanics

- Physics weapons: 1H sword, 2H axe, spear, shield (grab + pose constraints)
- Impact damage from velocity + edge alignment (simplified)
- 3 enemy types: Grunt, Shieldbearer, Brute
- Modes: Sandbox + Wave Survival
- Body locational damage stubs (head / torso / limbs)
- Comfort: teleport, snap turn, seated, height calibration

## Implement full UI

- Main menu (Sandbox / Waves / Arsenal / Settings / Credits)
- Arsenal rack: spawn / despawn weapons
- Wrist inventory: health, wave #, quick settings
- Health bar + damage vignette
- Wave banner + sandbox free-spawn radial
- Pause: resume / restart wave / comfort / quit
- Settings: locomotion, vignette, physics quality, seated

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/riftsteel-arena/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
