# Mythical Cards — Resource Packs

Official Unreal Studios Mythical Cards v1.3.3 Beta resource-pack downloads.

## Versioned assets

Download the files from [v1.3.3 Resource Packs](https://github.com/Official-Unreal-Studios/mythical-cards-resource-packs/releases/tag/v1.3.3-resource-packs).

| Minecraft client | Resource pack ZIP |
| --- | --- |
| 1.21–1.21.8 | `ResourcePack-1.21-1.21.8.zip` |
| 1.21.9–1.21.11 | `ResourcePack-1.21.9-1.21.11.zip` |
| 26.1–26.3 | `ResourcePack-26.1-26.3.zip` |

The machine-readable [manifest.json](manifest.json) contains download URLs, sizes and SHA-1 hashes for the Minecraft resource-pack prompt API.

On servers supporting multiple Minecraft client versions, the plugin should detect each joining player's client protocol (using ViaVersion when available), select the matching pack and show the standard resource-pack prompt. If the version is unknown or unsupported, do not send a guessed pack. Prompts should remain optional by default.

**Note:** Publishing these packs and the manifest does not automatically enable player join prompts in Mythical Cards. That is a separate plugin integration and requires Beta gameplay validation. Resource-pack ZIPs should remain immutable after publication: publish a new release and update the manifest when changing a pack.
