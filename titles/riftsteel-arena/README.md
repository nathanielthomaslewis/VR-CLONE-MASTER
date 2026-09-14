# Riftsteel Arena

**Working title:** Riftsteel Arena  
**Folder:** `titles/riftsteel-arena`  
**Genre inspiration (internal only):** Blade & Sorcery: Nomad (genre inspiration only — physics melee)  
**Ease note:** Hardest MVP — physics interaction depth. Selected for commercial success potential.

## Pitch

Physics melee sandbox — grab rift-forged steel, duel wave enemies or free-roam the arena, and master two-hand grips.

## Core mechanics (MVP)

- Physics weapons: 1H sword, 2H axe, spear, shield (grab + pose constraints)
- Impact damage from velocity + edge alignment (simplified)
- 3 enemy types: Grunt, Shieldbearer, Brute
- Modes: Sandbox + Wave Survival
- Body locational damage stubs (head / torso / limbs)
- Comfort: teleport, snap turn, seated, height calibration

## Full UI checklist

- [ ] Main menu (Sandbox / Waves / Arsenal / Settings / Credits)
- [ ] Arsenal rack: spawn / despawn weapons
- [ ] Wrist inventory: health, wave #, quick settings
- [ ] Health bar + damage vignette
- [ ] Wave banner + sandbox free-spawn radial
- [ ] Pause: resume / restart wave / comfort / quit
- [ ] Settings: locomotion, vignette, physics quality, seated

## Platforms (MVP targets)

- Meta Quest (App Lab path)
- SideQuest sideload
- Steam Frame (OpenXR / Android depot as applicable)
- Optional: PC VR OpenXR

## Engine

Godot 4 + OpenXR preferred. Document any Unity/Unreal deviation in `BUILD_MVP.md`.

## Assets

See [`ASSETS_NOTES.md`](ASSETS_NOTES.md). **Codex title.** No share with Breach Range combat stack. See `codex-vr-prompt/`.

## IP

Shipping name **Riftsteel Arena** only. Never use the inspiration title in UI, store copy, or asset filenames.
