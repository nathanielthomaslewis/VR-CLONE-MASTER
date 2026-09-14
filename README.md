# VR-CLONE-MASTER

Private vault of **MVP build prompts** for original SideQuest / Meta Quest / Steam Frame VR titles. Genre inspiration comes from high-demand SideQuest listings; every folder ships under an **original working title**.

> **Do not ship clones.** Do not copy names, art, levels, characters, UI, audio, or distinctive systems from cited commercial games. Treat those titles as market exemplars only.

**Engine preference:** Godot 4 + OpenXR (Quest / SideQuest / Steam Frame / PC VR). Unity or Unreal OpenXR OK if documented per title.

---

## Ease of build (easiest → hardest)

| Rank | Working title | Folder | Why this rank |
|------|---------------|--------|---------------|
| 1 | **Asphalt Spectre** | [`titles/asphalt-spectre`](titles/asphalt-spectre/) | Linear highway moto loop; few systems; strong juice on a narrow idea |
| 2 | **Rime Drift** | [`titles/rime-drift`](titles/rime-drift/) | Drift physics harder than highway moto, but **shares vehicle stack** with Asphalt Spectre |
| 3 | **Beastbound** | [`titles/beastbound-parkour`](titles/beastbound-parkour/) | Arm-swing locomotion + one parkour course; unique but scoped |
| 4 | **Breach Range** | [`titles/breach-range`](titles/breach-range/) | FPS feel + bot deathmatch; netcode stub adds risk |
| 5 | **Worldforge VR** | [`titles/worldforge-vr`](titles/worldforge-vr/) | God-sim breadth (terrain, creatures, rituals) — content surface is large |
| 6 | **Riftsteel Arena** | [`titles/riftsteel-arena`](titles/riftsteel-arena/) | Full physics melee (grab, swing, dismember stubs) — hardest MVP, **chosen for success** |

---

## Shared mechanics

### Driving stack (shared)

**Rime Drift** + **Asphalt Spectre** share:

- Vehicle chassis / wheels / suspension feel scaffolding
- Track / highway environment kit
- Race HUD (speed, lap, ghost, countdown)
- Ghost-lap replay

Place reusable art under [`shared-assets/vehicles/`](shared-assets/vehicles/) — **car** for drift, **bike** for moto, shared race UI meshes / icons.

### Combat presence (not shared)

| Title | Combat shape | Do not mix with |
|-------|--------------|-----------------|
| **Breach Range** | Hitscan / projectile FPS, reloads, bot AI | Physics melee grab |
| **Riftsteel Arena** | Physics weapons, two-hand grips, impact damage | FPS gun loop |

Keep input bindings, damage models, and inventory UX separate.

---

## Highest success potential → `codex-vr-prompt/`

**Pick: Riftsteel Arena** (physics melee sandbox — Blade & Sorcery: Nomad–*class* inspiration only).

**Why it wins:**

1. Proven **paid Quest / App Lab** demand for physics melee (SideQuest combat leaders).
2. **Single-player MVP** ships without multiplayer or anti-cheat.
3. Strong **SideQuest culture** for sandbox / combat toys that iterate in public.
4. Monetization path (premium App Lab / SideQuest paid) without live-ops day one.
5. Deep XR interaction demos well in store trailers.

Full codex: [`codex-vr-prompt/`](codex-vr-prompt/) — `BUILD_CODEX.md`, `IMAGE_PROMPTS.md`, `PROMPTS_3D.md`.

*(Runner-up: Breach Range for raw market size — deferred because FPS lobbies demand netcode + balance ops.)*

---

## Titles

| Working title | Genre inspiration (internal only) | Folder |
|---------------|-----------------------------------|--------|
| Breach Range | Pavlov Shack–class arena FPS | [`titles/breach-range`](titles/breach-range/) |
| Worldforge VR | Deisim–class god sandbox | [`titles/worldforge-vr`](titles/worldforge-vr/) |
| Riftsteel Arena | Blade & Sorcery: Nomad–class physics melee | [`titles/riftsteel-arena`](titles/riftsteel-arena/) |
| Beastbound | No More Rainbows–class arm parkour | [`titles/beastbound-parkour`](titles/beastbound-parkour/) |
| Rime Drift | CarX Real Drift–class VR drift | [`titles/rime-drift`](titles/rime-drift/) |
| Asphalt Spectre | Moto Rider VR–class highway racing | [`titles/asphalt-spectre`](titles/asphalt-spectre/) |

Each title folder contains:

- `README.md` — scope, mechanics, full UI checklist
- `BUILD_MVP.md` — agent prompt for working MVP level + UI
- `ASSETS_NOTES.md` — 3D / image needs + **shared asset** cross-links

---

## Layout

```
titles/              Per-title MVP prompts
shared-assets/       Cross-title kits (vehicles first)
asset-prompts/       Image/3D prompt packs per title + shared driving
codex-vr-prompt/     Deep build + asset prompts for Riftsteel Arena
SOUL.md              IP + product voice
LICENSE              MIT
```

Asset prompt index: [`asset-prompts/INDEX.md`](asset-prompts/INDEX.md).

## Licence

MIT — see `LICENSE`. Not affiliated with Meta, Valve, SideQuest, or any cited commercial game publishers.
