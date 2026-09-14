# BUILD_MVP — Worldforge VR

You are a VR game coding agent. Build a **playable MVP** for **Worldforge VR** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: Deisim (genre inspiration only — god sandbox). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Tiny world on your palm — raise terrain, plant biomes, guide creatures with ritual gestures.

## Implement these mechanics

- Table-scale diorama world (grab / scale / rotate)
- Terrain sculpt brush (raise / lower / smooth)
- 3 biomes + day/night slider
- Spawn 3 creature types with simple needs (hunger / joy)
- Ritual gestures: rain, quake, bless (cooldowns)

## Implement full UI

- Main menu (New World / Load / Gallery / Settings)
- Wrist palette: tools, biomes, creatures, rituals
- World stats panel (population, happiness)
- Pause + photo mode
- Settings: world scale, comfort, seated table height

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/worldforge-vr/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
