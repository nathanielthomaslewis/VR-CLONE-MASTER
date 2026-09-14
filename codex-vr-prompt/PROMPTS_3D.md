# PROMPTS_3D — Riftsteel Arena

Text-to-3D / retopo prompts. Export preference: **glTF 2.0**, metric scale, Y-up, separate materials, Quest LODs.

## Style lock

`low-poly stylised PBR, hard edges bevelled lightly, 2K textures max, emissive accents cyan/amber, clean UVs, no trademarks`

## Characters / enemies

1. `Grunt enemy humanoid, light armour plates, 1H weapon socket, A-pose, {style lock}, LOD0 15k tris`
2. `Shieldbearer enemy, larger tower shield, heavier stance, A-pose, {style lock}`
3. `Brute enemy, bulky, two-handed club socket, intimidating silhouette, A-pose, {style lock}`

## Weapons

4. `One-handed riftsteel sword, balanced blade, grip + guard separate materials, {style lock}`
5. `Two-handed battle axe, long haft, double bit, VR grab points marked, {style lock}`
6. `Spear with tip + shaft modules, {style lock}`
7. `Round shield with forearm grip and boss, {style lock}`

## Arena kit

8. `Modular arena floor tile stone-steel, 2m grid, {style lock}`
9. `Arena pillar + railing kit, snap modular, {style lock}`
10. `Weapon rack prop with empty hooks, {style lock}`
11. `Spawn pad glyph circle emissive, {style lock}`

## UI / VFX meshes

12. `World-space holographic panel frame, beveled rectangle, {style lock}`
13. `Wrist watch UI base mesh with screen quad, {style lock}`
14. `Impact spark mesh card set + rift fragment crystals, {style lock}`

## QA

- Scale check: sword ~90–110 cm; humanoid ~1.75 m
- Colliders: convex hulls for weapons; mesh for arena statics
- No NSFW; no real-world brand geometry
