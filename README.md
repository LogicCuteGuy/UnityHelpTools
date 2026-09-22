# LogicCuteGuy Help Tools

A collection of helpful Unity Editor tools for scene management, object manipulation, and optimization.

## Features

- **AutoScaleInLightmap**: Automatically scale objects in lightmap based on their world size.
- **CheckAssetUsageInScene**: Quickly find where assets are used in the current scene.
- **FixMissingShaderOnPrefab**: Repair prefabs with missing shader references.
- **PasteAsChildToAllParents**: Batch paste objects as children to multiple selected parents.
- **RandomRotateChildren**: Randomly rotate child objects for natural variation.
- **RandomSpawnChildrenOnNavMesh**: Spawn objects randomly on the NavMesh.
- **RemapComponentReferences**: Mass-update component references using patterns.
- **RenameChildrenIncrement**: Batch rename children with incremental numbers.
- **ReplaceChildMaterials**: Replace materials on all children in one click.
- **SelectChildrenByPattern**: Flexible selection of child objects using string patterns.
- **ShaderTextureMapper**: Map textures to shaders across multiple materials easily.
- **SortParentChildren**: Keep your hierarchy clean by sorting child objects.
- **SwitchChildLightmapMode**: Toggle lightmap modes for children (Baked/Realtime/None).
- **TerrainSwap**: Utility for swapping terrain data.

## Installation

### Via VPM / VRChat Creator Companion (recommended)
Add the LogicCuteGuy listing in **Settings > Packages > Add Repository**:
`https://vpm.logiccuteguy.com/index.json`

### Via Unity Package Manager (Disk)
1. Open the **Package Manager** in Unity (`Window > Package Manager`).
2. Click the **+** icon and select **Add package from disk...**.
3. Select the `package.json` file in this directory.

### Via Git URL
You can also add this package via Git URL:
`https://github.com/LogicCuteGuy/UnityHelpTools.git`

## Menu Commands

| Menu | Tools |
|---|---|
| **GameObject > LogicCuteGuy** | Auto Scale In Lightmap, Paste As Child To All Selected Parents, Random Rotate Children, Random Spawn Children On NavMesh, Rename Children Increment, Replace Or Remove Child Materials, Select Children By Pattern, Sort Parent Children |
| **Assets** | Check Usage in Scene, Fix Missing Shaders (Prefab → Standard) |
| **Window > LogicCuteGuy** | Shader Texture Mapper |
| **Component context menu** | Open Fix Cloned Component References (MonoBehaviour), Switch Child Lightmap Mode (MeshRenderer), Terrain Swap (Terrain) |

Tool windows include a built-in language switcher (English / 日本語 / ไทย).

Full documentation: [docs.logiccuteguy.com](https://docs.logiccuteguy.com/)

## Support
If you find these tools helpful, consider supporting my work:
[Donate/Support](https://profile.logiccuteguy.com/#donate)
