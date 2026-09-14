# BUILD_MVP — Beastbound

You are a VR game coding agent. Build a **playable MVP** for **Beastbound** (original IP).

## Hard rules

1. **Original IP** — genre inspiration may be cited only in comments/docs: No More Rainbows (genre inspiration only — arm locomotion parkour). No trademarked names, lookalikes of logos, or ripped assets.
2. **Engine:** Godot 4.x + OpenXR. XR hands / controllers via OpenXR action maps.
3. **Targets:** Meta Quest, SideQuest APK, Steam Frame, optional PC VR.
4. **Comfort:** teleport + snap default; smooth opt-in; seated support; vignette.
5. **Scope:** one working level/loop + **full UI** below — not a live-service clone.

## Pitch

Beast-bonded parkour — swing and vault through a neon canyon using arm locomotion; collect runes before the bond fades.

## Implement these mechanics

- Arm-swing / climb locomotion (no thumbstick walk as default)
- One vertical canyon course with checkpoints
- Grab ledges, poles, and beast-claw boost pads
- Collectible runes + timer challenge
- Fail / respawn at last checkpoint

## Implement full UI

- Main menu (Run / Practice / Settings)
- HUD: bond meter, rune count, split times
- Pause + comfort (reduce swing intensity)
- Results leaderboard (local)
- Settings: seated/standing, arm length calibration

## Acceptance criteria

- [ ] Boots into XR on Quest-class Android and desktop OpenXR
- [ ] Core loop playable for ≥5 minutes without softlocks
- [ ] All UI screens reachable and controller-navigable
- [ ] Comfort options persist
- [ ] No trademarked strings in user-facing text
- [ ] README in project root documents controls + export presets

## Deliverables

1. Godot project under `games/beastbound-parkour/` (or this folder if instructed)
2. Export notes for Quest / SideQuest / Steam Frame
3. Short CONTROL_MAP.md

## Out of scope (MVP)

Online multiplayer, UGC, battle pass, photo-real assets, full campaign narrative.
