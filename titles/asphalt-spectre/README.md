# Asphalt Spectre

**Working title:** Asphalt Spectre  
**Folder:** `titles/asphalt-spectre`  
**Genre inspiration (internal only):** Moto Rider VR: Highway Bike Racing (genre inspiration only)  
**Ease note:** Easiest — linear loop, few interactive objects.

## Pitch

Night highway motorcycle chase — lean into curves, weave traffic ghosts, beat the ghost-lap clock.

## Core mechanics (MVP)

- Seated or standing motorcycle stance with controller lean / stick lean
- One infinite-scroll highway segment + three scenic variants (city, coastal, desert night)
- Traffic obstacles as simple capsule movers (no AI drivers MVP)
- Ghost lap + personal best timer
- Boost meter + crash / recover

## Full UI checklist

- [ ] Main menu (Play / Garage / Settings / Quit)
- [ ] Garage: bike paint + boost tune (3 presets)
- [ ] In-ride HUD: speed, boost, lap time, ghost delta
- [ ] Pause: resume / restart / comfort / quit
- [ ] Results: PB vs ghost, retry / next route
- [ ] Settings: comfort vignette, seated height, snap vs smooth look

## Platforms (MVP targets)

- Meta Quest (App Lab path)
- SideQuest sideload
- Steam Frame (OpenXR / Android depot as applicable)
- Optional: PC VR OpenXR

## Engine

Godot 4 + OpenXR preferred. Document any Unity/Unreal deviation in `BUILD_MVP.md`.

## Assets

See [`ASSETS_NOTES.md`](ASSETS_NOTES.md). **Shared:** `shared-assets/vehicles/` — bike chassis + race UI + asphalt kit with Rime Drift.

## IP

Shipping name **Asphalt Spectre** only. Never use the inspiration title in UI, store copy, or asset filenames.
