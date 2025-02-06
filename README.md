# Survival Ultra Vanilla

- Minecraft: 1.21.1
- Fabric: 0.16.10
- Java: 21.0.5.11 Adoptium (Temurin) (via sdkman)
- Screen Resolution: 1440x900
- Packwiz
- Packwiz Installer
- Packwiz Installer Bootstrap: 0.0.3

## Mods

### Installation

- Run `packwiz serve`
- Copy the following command to `PrismLauncher instance > Configuration > Custom
Commands > Pre-launch command`:

  ```bash
  "$INST_JAVA" -jar packwiz-installer-bootstrap.jar http://localhost:8080/pack.toml
  ```

- Run the `PrismLauncher instance` and wait for the installation to finish
- Once the installation is finished, disable the `Custom Commands` and kill the
  packwiz server.

### Update

Run the same commands as the installation.

### Optimization

- `Alternate Current`: 1.9.0
- `BadOptimizations`: 2.2.1
- `Clumps`: 19.0.0.1 _(Disable when battle the Ender Dragon)_
  - `Fabric API`: 0.110.0
- `Concurrent Chunk Management Engine`: 0.3.0+alpha.0.306
- `Debugify`: 1.0
- `Enhanced Block Entities`: 0.10.2
- `EntityCulling`: 1.7.2
- `Fast Paintings`: 1.2.15 (Once I place paintings)
  - `Moonlight Lib`: 2.17.7
- `Fast Async World Save`: 2.0
  - `Cupboard`: 2.7
- `FerriteCore`: 7.0.2-hotfix-fabric
- `FPS Reducer`: 2.9
- `Get It Together, Drops!`: 1.3.1
  - `Cloth Config API`: 15.0.140
- `ImmediatelyFast`: 1.3.3
- `Ksyxis`: 1.3.2
- `Let Me Despawn`: 1.4.4
  - `Almanac Lib`: 1.0.2
- `Limited Chunkloading - Chunk cleanup`: 4.1
  - `Cupboard`: 2.7
- `Lithium`: 0.14.3
- `ModernFix`: 5.19.6
- `More Culling`: 1.0.1
  - `Cloth Config API`: 15.0.140
- `Noisium`: 2.3.0
- `Not Enough Recipe Book`: 0.4.1 (Disabled recipe book icon)
  - `Architectury API`: 13.0.8
  - `OctoLib`: 0.4.2
- `Particle Core`: 0.2.4
  - `Fabric Language Kotlin`: 1.13.0.+kotlin.2.1.0
  - `Fzzy Config`: 0.5.9
- `Server Performance - Smooth Chunk Save`: 3.8
  - `Cupboard`: 2.7
- `Sodium`: 0.6.3
- `Sodium/Embeddium Extras`: 1.0.6
  - `Sodium/Embeddium Options API`: 1.0.8
    - `Reese's Sodium Options`: 1.8.0
- `Sodium Extra`: 0.6.0

### Useful

- `Fast Backups`: 0.19.0
- `hotbar-keys`: 0.0.0 (Local build of `1.21` branch at commit `a036131`)
- `JEI`: 19.21.0.247
- `Mod Menu`: 11.0.3
  - `Text Placeholder API`: 2.4.1
- `Mouse Tweaks`: 2.26
- `NetherPortalFix`: 21.1.1
  - `Balm`: 21.0.20
- `Notes`: 2.1.1
- `Paginated Advancements & Custom Frames`: 2.5.1
- `Shulker Box ToolTip`: 5.1.2
- `Spyglass Improvements`: 1.5.7
- `Text Formatting Everywhere`: 1.0.1
- `Time On Display`: 2.0.0
  - `MonoLib`: 2.0.0

### Miscellaneous

- `AmbientSounds`: 6.1.4
  - `CreativeCore`: 2.12.23
  - Disabled features:
    - Cave sounds except `regions.cave_lush.cave-lush`
- `Animatica`: 0.6.1
  - Required by `Recolourful Containers GUI + HUD (DARK)` resource pack
- `CIT Resewn`: 1.2.2
  - Required by:
    - `Visual Armor Trims` resource pack
    - `xali's Enchanted Books` resource pack
- `Continuity`: 3.0.0
- `Customizable Elytra`: 2.2.7
- `Cycle Paintings`: 3.6 (set as `client` side)
  - `Collective`: 7.87
- `Dark Paintings`: 21.1.2
  - `Bookshelf`: 21.1.48
  - `Prickle`: 21.1.6
- `Eating Animation`: 1.9.72
- `Entity Model Features`: 2.2.6
  - `Entity Texture Features`: 6.2.9
    - Required by `Better Enchanting Table` resource pack
  - Required by:
    - `Better Boats` resource pack
    - `Human Era Villagers` resource pack
- `FabricSkyBoxes`: 0.7.4
  - Required by `Dramatic Skys` resource pack
- `Falling Leaves`: 1.16.4
- `First-person Model`: 2.4.6 (Only when battle Warden, Ender Dragon or Whither
  Boss)
- `Glowing Torchflower`: 1.2.0
- `Legendary Tooltips`: 1.4.11
  - `Iceberg`: 1.2.7
  - `Prism`: 1.0.9
- `Litematica`: 0.19.53 (Only when building)
  - `MaLiLib`: 0.21.4
- `Not Enough Animations`: 1.8.2
- `OptiGUI`: 2.3.0-beta.6
  - Required by `Recolourful Containers GUI + HUD (DARK)` resource pack
- `Particular`: 1.1.1
  - `owo-lib`: 0.12.15
  - Disabled features:
    - Rain dripples
    - Falling leaves
- `Polytone`: 2.5.13
  - Required by `Shrimp's Distinct Potions` resource pack
- `Serene Seasons`: 10.1.0.1
  - `GlitchCore`: 2.1.0.0
  - **NOTE**: Try to set `sub_season_duration` to another value. `8` means `8
Minecraft days` that is equal to `80 minutes IRL`
- `SkinChanger`: 0.9.2
  - `Architectury API`: 13.0.8
- `Tool trims`: 2.2.2
- `Visual Overhaul`: 5.2.1
- `Visual Workbench`: 21.1.0
  - `Forge Config API Port`: 21.1.3
  - `Puzzles Lib`: 21.1.27
- `Visuality`: 0.7.7 (Disabled Slime and Hit FX)
  - `Cloth Config API`: 15.0.140

## Resource Packs

- `3d crops Revamped`: 1
- `Better Boat`: 1
- `Better Carpets`: 0.1 (1.19.4)
- `Better Enchanting Table`: 1.1
- `Better Lanterns`: 1.2
- `Blocky Saplings`: 1.1
- `Continuity (mod) built-in resource packs`
  - `Default Connected Textures`
  - `Glass Pane Culling Fix`
- `Creepers Reimagined`: 1.2
- `Default Dark Mode: Expansion`: 2024.11.10
- `Dramatic Skys`: 1.5.3.30
- `Eating Animation (mod) built-in resource packs`
  - `minecraft/supporteatinganimation`
- `Enchant Icons`: 1.3
- `Enchanting Table Magic Circle`: 1.3
- `Enhanced Item Frame`: 1.21
- `Fancy Beds`: 3.4
- `FancyConnectedBeds`: (Downloaded from [BetterBeds
  repository](https://github.com/TeamMidnightDust/BetterBeds))
- `Fast Better Grass`: 1.21.4
- `Hatsune Miku Totem`: 1.0
- `hdoc-vt-rp-1.21.x`: [Click to download](https://vanillatweaks.net/share#gTMUJ0)
- `Human Era Villagers`: HumanVillagerOnly 2.75
- `Hunger Preview`: 1.21
- `Improved Fences`: 1.2.5
- `Improved Fences Single-Door Gate Add-On`: 1.1 (Downloaded from [Improved
  Fences repository](https://github.com/NaiNonTH/Improved-Fences))
- `Improved Fences All Planks Add-On`: 1.2.2 (Downloaded from [Improved
  Fences repository](https://github.com/NaiNonTH/Improved-Fences))
- `Minecarts with Wheels`: 1.1.0
- `Recolourful Containers GUI + HUD (DARK)`: 1.1.1
- `Round Trees`: 7.1
- `Shrimp's Distinct Potions`: 1.1
- `Simple Grass Flowers`: 1.9.2
- `Spryzeen's Knight Armor`: 1.8
- `Taiga Painting`: 1.0
- `Torches Reimagined`: 1.3.1
- `Varied Pumpkins`: 1.2
- `Visual Armor Trims`: 2.1
- `Visual Overhaul (mod) built-in resource packs`
  - `visualoverhaul/rounddiscs`
  - `visualoverhaul/fancyfurnace`
  - `visualoverhaul/nobrewingbottles`
- `xali's Enchanted Books`: 0.13.0

### Required Order

#### GUI

1. `hdoc-vt-rp`
2. `Recolourful Containers GUI + HUD (DARK)`
3. `Default Dark Mode: Expansion`

#### Grass

1. `Simple Grass Flowers`
2. `Fast Better Grass`

#### Armor

1. `hdoc-vt-rp`
2. `Spryzeen's Knight Armor`

## Backup

### Configuration

Run the following commands once opened `Minecraft`:

1. `/backup set shutdown-action full-gc`
2. `/backup set retention-policy daily 7`
3. `/backup set remote-retention-policy daily 7`
4. `/backup create-file-remote ${path_to_this_repo}/backup`

> [!NOTE]
> `${path_to_this_repo}` is the absolute path to this repository.

### Compressed Backup

Run the following command:

```bash
env GZIP=-9 tar cvzf survival-ultra-vanilla-bkp.tar.gz backup
```
