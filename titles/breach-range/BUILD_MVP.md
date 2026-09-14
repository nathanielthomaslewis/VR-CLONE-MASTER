# BUILD_MVP — Breach Range

You are a VR game coding agent. Build a **playable MVP** for **Breach Range** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: Pavlov Shack (genre inspiration only — arena FPS). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Tactical range + bot deathmatch — train reloads and peeks offline, then fight bots on one warehouse map.

## Implement these mechanics

- Two-handed gun grab, mag reload, slide rack
- Offline shooting range with moving targets
- One warehouse deathmatch vs 4 bots (navmesh)
- 3 weapons: pistol, SMG, shotgun
- Netcode **stub** only (local multiplayer placeholder; online out of MVP)

## Implement full UI

- Main menu (Range / Deathmatch / Loadout / Settings)
- Loadout: weapon + attachment presets
- In-game: ammo, health, scoreboard, killfeed
- Wrist watch: map / mute / leave
- Pause + comfort (snap turn, teleport option in range)
- Post-match summary

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/breach-range/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
