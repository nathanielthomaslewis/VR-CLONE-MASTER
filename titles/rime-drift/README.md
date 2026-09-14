# Rime Drift

**Working title:** Rime Drift  
**Folder:** `titles/rime-drift`  
**Genre inspiration (internal only):** CarX Real Drift Racing (genre inspiration only)  
**Ease note:** Harder than highway moto due to drift feel tuning; still shares vehicle stack.

## Pitch

Mountain drift circuit — initiate, hold angle, score style chains before the frost timer runs out.

## Core mechanics (MVP)

- Arcade drift physics (grip → slip → sustained angle scoring)
- One closed mountain circuit (MVP) + optional second layout
- Style score multipliers (combo, near-miss barriers)
- Ghost lap of best run
- Simple damage / smoke on hard wall hits (cosmetic)

## Full UI checklist

- [ ] Main menu (Career Time Attack / Free Drift / Settings)
- [ ] Car select (3 liveries; shared chassis)
- [ ] HUD: speed, drift angle meter, combo, sector times
- [ ] Pause + comfort
- [ ] Results / replay ghost
- [ ] Settings: assist levels, vignette, seated cockpit camera

## Platforms (MVP targets)

- Meta Quest (App Lab path)
- SideQuest sideload
- Steam Frame (OpenXR / Android depot as applicable)
- Optional: PC VR OpenXR

## Engine

Godot 4 + OpenXR preferred. Document any Unity/Unreal deviation in `BUILD_MVP.md`.

## Assets

See [`ASSETS_NOTES.md`](ASSETS_NOTES.md). **Shared:** `shared-assets/vehicles/` — **car** + race UI with Asphalt Spectre. Note: car for drift; bike remains Asphalt-primary.

## IP

Shipping name **Rime Drift** only. Never use the inspiration title in UI, store copy, or asset filenames.
