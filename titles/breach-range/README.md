# Breach Range

**Working title:** Breach Range  
**Folder:** `titles/breach-range`  
**Genre inspiration (internal only):** Pavlov Shack (genre inspiration only — arena FPS)  
**Ease note:** Harder — gun feel + bot AI; netcode stub is a future hook.

## Pitch

Tactical range + bot deathmatch — train reloads and peeks offline, then fight bots on one warehouse map.

## Core mechanics (MVP)

- Two-handed gun grab, mag reload, slide rack
- Offline shooting range with moving targets
- One warehouse deathmatch vs 4 bots (navmesh)
- 3 weapons: pistol, SMG, shotgun
- Netcode **stub** only (local multiplayer placeholder; online out of MVP)

## Full UI checklist

- [ ] Main menu (Range / Deathmatch / Loadout / Settings)
- [ ] Loadout: weapon + attachment presets
- [ ] In-game: ammo, health, scoreboard, killfeed
- [ ] Wrist watch: map / mute / leave
- [ ] Pause + comfort (snap turn, teleport option in range)
- [ ] Post-match summary

## Platforms (MVP targets)

- Meta Quest (App Lab path)
- SideQuest sideload
- Steam Frame (OpenXR / Android depot as applicable)
- Optional: PC VR OpenXR

## Engine

Godot 4 + OpenXR preferred. Document any Unity/Unreal deviation in `BUILD_MVP.md`.

## Assets

See [`ASSETS_NOTES.md`](ASSETS_NOTES.md). **Not shared with Riftsteel.** FPS damage + inventory differ from physics melee.

## IP

Shipping name **Breach Range** only. Never use the inspiration title in UI, store copy, or asset filenames.
