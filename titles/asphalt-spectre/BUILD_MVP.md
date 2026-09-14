# BUILD_MVP — Asphalt Spectre

You are a VR game coding agent. Build a **playable MVP** for **Asphalt Spectre** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: Moto Rider VR: Highway Bike Racing (genre inspiration only). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Night highway motorcycle chase — lean into curves, weave traffic ghosts, beat the ghost-lap clock.

## Implement these mechanics

- Seated or standing motorcycle stance with controller lean / stick lean
- One infinite-scroll highway segment + three scenic variants (city, coastal, desert night)
- Traffic obstacles as simple capsule movers (no AI drivers MVP)
- Ghost lap + personal best timer
- Boost meter + crash / recover

## Implement full UI

- Main menu (Play / Garage / Settings / Quit)
- Garage: bike paint + boost tune (3 presets)
- In-ride HUD: speed, boost, lap time, ghost delta
- Pause: resume / restart / comfort / quit
- Results: PB vs ghost, retry / next route
- Settings: comfort vignette, seated height, snap vs smooth look

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/asphalt-spectre/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
