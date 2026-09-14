# BUILD_MVP — Rime Drift

You are a VR game coding agent. Build a **playable MVP** for **Rime Drift** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: CarX Real Drift Racing (genre inspiration only). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Mountain drift circuit — initiate, hold angle, score style chains before the frost timer runs out.

## Implement these mechanics

- Arcade drift physics (grip → slip → sustained angle scoring)
- One closed mountain circuit (MVP) + optional second layout
- Style score multipliers (combo, near-miss barriers)
- Ghost lap of best run
- Simple damage / smoke on hard wall hits (cosmetic)

## Implement full UI

- Main menu (Career Time Attack / Free Drift / Settings)
- Car select (3 liveries; shared chassis)
- HUD: speed, drift angle meter, combo, sector times
- Pause + comfort
- Results / replay ghost
- Settings: assist levels, vignette, seated cockpit camera

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/rime-drift/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
