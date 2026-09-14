# ASSETS_NOTES — Asphalt Spectre

Original art only. Stylised low-poly PBR, Quest LODs.

## Image prompts (concept / mood)

1. Key art: Asphalt Spectre — Night highway motorcycle chase — lean into curves, weave traffic ghosts, beat the ghost-lap clock.…
2. UI mock: main menu holographic panels, dark neon, readable at VR distance
3. Environment establishing shot of the MVP level
4. Hero prop / vehicle / weapon close-up (title-specific)
5. Comfort / seated play reference silhouette

## 3D generation prompts (glTF-ready)

1. Hero interactive object (vehicle, weapon, or tool) — clean topology, separate materials
2. Environment modular kit (10–20 pieces)
3. 1–3 character / enemy / rider proxies with LODs
4. UI world-space panels + icons (atlas)
5. VFX meshes: boost trail / impact sparks / rune glow as needed

## Style bible

- Palette: high-contrast emissives on dark bases for Quest contrast
- Avoid copying any commercial game silhouette
- Filename prefix: `asphalt_spectre_`

**Shared:** `shared-assets/vehicles/` — bike chassis + race UI + asphalt kit with Rime Drift.

## Shared assets (required cross-link)

See [`../../shared-assets/vehicles/`](../../shared-assets/vehicles/).

| Need | Path hint | Shared with |
|------|-----------|-------------|
| Car hero | `shared-assets/vehicles/veh_car_*` | Rime Drift primary |
| Bike hero | `shared-assets/vehicles/veh_bike_*` | Asphalt Spectre primary |
| Race UI | `shared-assets/vehicles/ui_race_*` | Both |
| Asphalt / barrier kit | `shared-assets/vehicles/env_asphalt_*` | Both |
