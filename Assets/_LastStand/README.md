# Last Stand Custom Project Area

All original Last Stand work lives under `Assets/_LastStand`. Third-party assets stay in their imported folders and are never edited directly:

- `Assets/Julhiecio TPS Controller`
- `Assets/JUTPS Addons`
- `Assets/Synty`

These folders are not included in the repository. See the root [README](../../README.md#running-the-project).

## Structure

| Folder | Contents |
|---|---|
| `Scenes` | `LS_MainMenu.unity` (entry scene) and `LS_Arena_01.unity` (gameplay arena with baked NavMesh) |
| `Scripts` | Custom gameplay systems, one folder and namespace per responsibility: `AI`, `GameFlow`, `Pickups`, `Spawning`, `Stats`, `UI`, `Waves` |
| `ScriptableObjects` | Enemy definitions, wave definitions and the enemy drop table |
| `Prefabs/Enemies` | Project-owned wrapper prefabs for the fist, knife and ranged enemies |

See [Docs/ARCHITECTURE.md](../../Docs/ARCHITECTURE.md) for how the systems fit together.
