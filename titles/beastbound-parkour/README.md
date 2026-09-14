# Beastbound

**Working title:** Beastbound  
**Folder:** `titles/beastbound-parkour`  
**Genre inspiration (internal only):** No More Rainbows (genre inspiration only — arm locomotion parkour)  
**Ease note:** Unique locomotion but one-level scope keeps it mid-easy.

## Pitch

Beast-bonded parkour — swing and vault through a neon canyon using arm locomotion; collect runes before the bond fades.

## Core mechanics (MVP)

- Arm-swing / climb locomotion (no thumbstick walk as default)
- One vertical canyon course with checkpoints
- Grab ledges, poles, and beast-claw boost pads
- Collectible runes + timer challenge
- Fail / respawn at last checkpoint

## Full UI checklist

- [ ] Main menu (Run / Practice / Settings)
- [ ] HUD: bond meter, rune count, split times
- [ ] Pause + comfort (reduce swing intensity)
- [ ] Results leaderboard (local)
- [ ] Settings: seated/standing, arm length calibration

## Platforms (MVP targets)

- Meta Quest (App Lab path)
- SideQuest sideload
- Steam Frame (OpenXR / Android depot as applicable)
- Optional: PC VR OpenXR

## Engine

Godot 4 + OpenXR preferred. Document any Unity/Unreal deviation in `BUILD_MVP.md`.

## Assets

See [`ASSETS_NOTES.md`](ASSETS_NOTES.md). **No shared vehicle assets.** Optional shared comfort vignette shaders only.

## IP

Shipping name **Beastbound** only. Never use the inspiration title in UI, store copy, or asset filenames.
