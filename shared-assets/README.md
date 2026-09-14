# Shared assets

Cross-title kits used by more than one MVP. **Do not** put Riftsteel / Breach combat meshes here — those systems do not share.

## `vehicles/`

Used by:

| Asset family | Primary title | Also used by |
|--------------|---------------|--------------|
| **Car** chassis + wheels + interior cockpit | Rime Drift | (optional ghost car in Asphalt Spectre demos) |
| **Bike** chassis + rider proxy | Asphalt Spectre | — |
| **Race UI** (speedo, lap counter, countdown rings, ghost ghost-line) | Both | Both |
| Highway / asphalt prop kit | Asphalt Spectre | Rime Drift (mountain / coastal variants OK) |

### Prompt notes for image / 3D bots

- Style: stylised low-poly PBR, Quest-friendly LODs (target ~30–80k tris per hero vehicle).
- **Shared race UI:** flat icons + world-space holographic panels; avoid copying any commercial HUD.
- Filename convention: `veh_car_*`, `veh_bike_*`, `ui_race_*`, `env_asphalt_*`.

Placeholder folders live under `vehicles/` — drop glTF / FBX when generated.
