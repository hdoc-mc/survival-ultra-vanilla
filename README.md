# Survival Ultra Vanilla

- Minecraft: 1.21.1
- Fabric: 0.16.10
- Java: 21.0.5.11 [Eclipse Adoptium Temurin][jdk-temurin]
  ([via sdkman][jdk-temurin-sdkman])
- Screen Resolution: 1440x900
- [Packwiz](https://github.com/packwiz/packwiz)
- [Packwiz Installer](https://github.com/packwiz/packwiz-installer)
- [Packwiz Installer Bootstrap][packwiz-installer-bootstrap]:
  [0.0.3][packwiz-installer-bootstrap-version]

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

- [`Alternate Current`](https://modrinth.com/mod/alternate-current): 1.9.0
- [`BadOptimizations`](https://modrinth.com/mod/badoptimizations): 2.2.1
- [`Clumps`](https://modrinth.com/mod/clumps): 19.0.0.1 _(Disable when battle
  the Ender Dragon)_
- [`Concurrent Chunk Management Engine`](https://modrinth.com/mod/c2me-fabric):
  0.3.0+alpha.0.306
- [`Debugify`](https://modrinth.com/mod/debugify): 1.0
- [`Enhanced Block Entities`](https://modrinth.com/mod/ebe): 0.10.2
- [`EntityCulling`](https://modrinth.com/mod/entityculling): 1.7.2
- [`Fabric API`](https://modrinth.com/mod/fabric-api): 0.110.0
- [`Fast Paintings`](https://modrinth.com/mod/fast-paintings): 1.2.15 (Once I
  place paintings)
  - [`Moonlight Lib`](https://modrinth.com/mod/moonlight): 2.17.7
- [`Fast Async World Save`][fast-async-world-save]: 2.0
  - [`Cupboard`](https://www.curseforge.com/minecraft/mc-mods/cupboard): 2.7
- [`FerriteCore`](https://modrinth.com/mod/ferrite-core): 7.0.2-hotfix-fabric
- [`FPS Reducer`](https://modrinth.com/mod/fps-reducer): 2.9
- [`Get It Together, Drops!`](https://modrinth.com/mod/get-it-together-drops):
  1.3.1
  - [`Cloth Config API`](https://modrinth.com/mod/cloth-config): 15.0.140
- [`ImmediatelyFast`](https://modrinth.com/mod/immediatelyfast): 1.3.3
- [`Ksyxis`](https://modrinth.com/mod/ksyxis): 1.3.2
- [`Let Me Despawn`](https://modrinth.com/plugin/lmd): 1.4.4
  - [`Almanac Lib`](https://modrinth.com/mod/almanac): 1.0.2
- [`Limited Chunkloading - Chunk cleanup`][limited-chunk-loading]: 4.1
  - `Cupboard`: 2.7
- [`Lithium`](https://modrinth.com/mod/lithium): 0.14.3
- [`ModernFix`](https://modrinth.com/mod/modernfix): 5.19.6
- [`More Culling`](https://modrinth.com/mod/moreculling): 1.0.1
  - `Cloth Config API`: 15.0.140
- [`Noisium`](https://modrinth.com/mod/noisium): 2.3.0
- [`Not Enough Recipe Book`](https://modrinth.com/mod/notenoughrecipebook):
  0.4.1 (Disabled recipe book icon)
  - [`Architectury API`](https://modrinth.com/mod/architectury-api): 13.0.8
  - [`OctoLib`](https://modrinth.com/mod/octo-lib): 0.4.2
- [`Particle Core`](https://modrinth.com/mod/particle-core): 0.2.4
  - [`Fabric Language Kotlin`](https://modrinth.com/mod/fabric-language-kotlin):
    1.13.0.+kotlin.2.1.0
  - [`Fzzy Config`](https://modrinth.com/mod/fzzy-config): 0.5.9
- [`Server Performance - Smooth Chunk Save`][server-performance]: 3.8
  - `Cupboard`: 2.7
- [`Sodium`](https://modrinth.com/mod/sodium): 0.6.3
- [`Sodium Extras`](https://modrinth.com/mod/sodium-extras): 1.0.6
  - [`Sodium Options API`](https://modrinth.com/mod/sodium-options-api): 1.0.8
    - [`Reese's Sodium Options`](https://modrinth.com/mod/reeses-sodium-options):
      1.8.0
- [`Sodium Extra`](https://modrinth.com/mod/sodium-extra): 0.6.0

### Useful

- [`Fast Backups`](https://modrinth.com/mod/fastback): 0.19.0
- [`hotbar-keys`][hotbar-keys-repo]: 0.0.0 (Local build of
  [`1.21`][hotbar-keys-branch] branch at commit [`a036131`][hotbar-keys-commit])
- [`JEI`](https://modrinth.com/mod/jei): 19.21.0.247
- [`Mod Menu`](https://modrinth.com/mod/modmenu): 11.0.3
  - [`Text Placeholder API`](https://modrinth.com/mod/placeholder-api): 2.4.1
- [`Mouse Tweaks`](https://modrinth.com/mod/mouse-tweaks): 2.26
- [`NetherPortalFix`](https://modrinth.com/mod/netherportalfix): 21.1.1
  - [`Balm`](https://modrinth.com/mod/balm): 21.0.20
- [`Notes`](https://modrinth.com/mod/notes): 2.1.1
- [`Paginated Advancements & Custom Frames`][paginated-advancements]: 2.5.1
- [`Shulker Box ToolTip`](https://modrinth.com/mod/shulkerboxtooltip): 5.1.2
- [`Spyglass Improvements`](https://modrinth.com/mod/spyglass-improvements):
  1.5.7
- [`Text Formatting Everywhere`][text-formatting]: 1.0.1
- [`Time On Display`](https://modrinth.com/mod/time-on-display): 2.0.0
  - [`MonoLib`](https://modrinth.com/mod/monolib): 2.0.0

### Miscellaneous

- [`AmbientSounds`](https://modrinth.com/mod/ambientsounds): 6.1.4
  - [`CreativeCore`](https://modrinth.com/mod/creativecore): 2.12.23
  - Disabled features:
    - Cave sounds except `regions.cave_lush.cave-lush`
- [`Animatica`](https://modrinth.com/mod/animatica): 0.6.1
  - Required by `Recolourful Containers GUI + HUD (DARK)` resource pack
- [`CIT Resewn`](https://modrinth.com/mod/cit-resewn): 1.2.2
  - Required by:
    - `xali's Enchanted Books` resource pack
- [`Continuity`](https://modrinth.com/mod/continuity): 3.0.0
- [`Cycle Paintings`](https://modrinth.com/mod/cycle-paintings): 3.6 (set as
  `client` side)
  - [`Collective`](https://modrinth.com/mod/collective): 7.87
- [`Dark Paintings`](https://modrinth.com/mod/dark-paintings): 21.1.2
  - [`Bookshelf`](https://modrinth.com/mod/bookshelf-lib): 21.1.48
  - [`Prickle`](https://modrinth.com/mod/prickle): 21.1.6
- [`Eating Animation`](https://modrinth.com/mod/eating-animation): 1.9.72
- [`Entity Model Features`](https://modrinth.com/mod/entity-model-features): 2.2.6
  - [`Entity Texture Features`](https://modrinth.com/mod/entitytexturefeatures):
    6.2.9
    - Required by `Better Enchanting Table` resource pack
  - Required by:
    - `Better Boats` resource pack
    - `Human Era Villagers` resource pack
- [`FabricSkyBoxes`](https://modrinth.com/mod/nuit): 0.7.4
  - Required by `Dramatic Skys` resource pack
- [`Falling Leaves`](https://modrinth.com/mod/fallingleaves): 1.16.4
- [`First-person Model`](https://modrinth.com/mod/first-person-model): 2.4.6
  (Only when battle Warden, Ender Dragon or Whither Boss)
- [`Glowing Torchflower`](https://modrinth.com/mod/glowing-torchflower): 1.2.0
- [`Legendary Tooltips`](https://modrinth.com/mod/legendary-tooltips): 1.4.11
  - [`Iceberg`](https://modrinth.com/mod/iceberg): 1.2.7
  - [`Prism`](https://modrinth.com/mod/prism-lib): 1.0.9
- [`Litematica`](https://modrinth.com/mod/litematica): 0.19.53 (Only when
  building)
  - [`MaLiLib`](https://modrinth.com/mod/malilib): 0.21.4
- [`Not Enough Animations`](https://modrinth.com/mod/not-enough-animations):
  1.8.2
- [`OptiGUI`](https://modrinth.com/mod/optigui): 2.3.0-beta.6
  - Required by `Recolourful Containers GUI + HUD (DARK)` resource pack
- [`Particular`](https://modrinth.com/mod/particular): 1.1.1
  - [`owo-lib`](https://modrinth.com/mod/owo-lib): 0.12.15
  - Disabled features:
    - Falling leaves
    - Rain dripples
    - Water Drip Ripples
- [`Polytone`](https://modrinth.com/mod/polytone): 2.5.13
  - Required by `Shrimp's Distinct Potions` resource pack
- [`Serene Seasons`](https://modrinth.com/mod/serene-seasons): 10.1.0.1
  - [`GlitchCore`](https://modrinth.com/mod/glitchcore): 2.1.0.0
  - **NOTE**: Try to set `sub_season_duration` to another value. `8` means 8
    Minecraft days that is equal to 80 minutes IRL
- [`SkinChanger`](https://modrinth.com/mod/skinchanger): 0.9.2
  - `Architectury API`: 13.0.8
- [`Visual Overhaul`](https://modrinth.com/mod/visual-overhaul): 5.2.1
- [`Visual Workbench`](https://modrinth.com/mod/visual-workbench): 21.1.0
  - [`Forge Config API Port`](https://modrinth.com/mod/forge-config-api-port):
    21.1.3
  - [`Puzzles Lib`](https://modrinth.com/mod/puzzles-lib): 21.1.27
- [`Visuality`](https://modrinth.com/mod/visuality): 0.7.7 (Disabled Slime and
  Hit FX)
  - `Cloth Config API`: 15.0.140

## Resource Packs

- [`3d crops Revamped`](https://modrinth.com/resourcepack/3d-crops): 1
- [`Ancient N Decked`](https://modrinth.com/resourcepack/ancient-n-decked): 1.2
- [`Better Boat`](https://modrinth.com/resourcepack/better-boat): 1
- [`Better Carpets`](https://modrinth.com/resourcepack/better-carpets): 0.1
  (1.19.4)
- [`Better Enchanting Table`][better-enchanting-table]: 1.1
- [`Better Lanterns`](https://modrinth.com/resourcepack/better-lanterns): 1.2
- [`Blocky Saplings`](https://modrinth.com/resourcepack/blocky-saplings): 1.1
- `Continuity (mod) built-in resource packs`
  - `Default Connected Textures`
  - `Glass Pane Culling Fix`
- [`Creepers Reimagined`][creepers-reimagined]: 1.2
- [`Default Dark Mode: Expansion`][default-dark-mode-expansion]: 2024.11.10
- [`Dramatic Skys`](https://modrinth.com/resourcepack/dramatic-skys): 1.5.3.30
- `Eating Animation (mod) built-in resource packs`
  - `minecraft/supporteatinganimation`
- [`Enchant Icons`](https://modrinth.com/resourcepack/enchant-icons-countxd): 1.3
- [`Enchanting Table Magic Circle`][enchanting-table-magic-circle]: 1.3
- [`Enhanced Item Frame`][enhanced-item-frame]: 1.21
- [`Fancy Beds`](https://modrinth.com/resourcepack/fancy-beds): 3.4
- `FancyConnectedBeds`: (Downloaded from [BetterBeds
  repository](https://github.com/TeamMidnightDust/BetterBeds))
- [`Fast Better Grass`](https://modrinth.com/resourcepack/fast-better-grass):
  1.21.4
- [`fishing hook bobber 3D`][fishing-hook-bobber]: 2.1-fancy-line
- [`Hatsune Miku Totem`](https://modrinth.com/resourcepack/hatsune-miku-totem):
  1.0
- `hdoc-vt-rp-1.21.x`: [Click to download](https://vanillatweaks.net/share#TMdEn4)
- [`Human Era Villagers`][human-era-villagers]: HumanVillagerOnly 2.75
- [`Hunger Preview`][hunger-preview]: 1.21
- [`Improved Fences`](https://modrinth.com/resourcepack/improved-fences): 1.2.5
- `Improved Fences Single-Door Gate Add-On`: 1.1 (Downloaded from [Improved
  Fences repository](https://github.com/NaiNonTH/Improved-Fences))
- `Improved Fences All Planks Add-On`: 1.2.2 (Downloaded from [Improved
  Fences repository](https://github.com/NaiNonTH/Improved-Fences))
- [`Minecarts with Wheels`][minecarts-with-wheels]: 1.1.0
- [`Spryzeen's Ore Glint`][ore-glint]: 1.7 for Sodium
- [`Recolourful Containers GUI + HUD (DARK)`][recolourful-containers]: 1.1.1
- [`Round Trees`](https://modrinth.com/resourcepack/round-trees): 7.1
- [`XXVI's Shiny Armor Trims`][shiny-armor-trims]: v5 (Vanilla Animated)
  (Downloaded from [Curseforge Page][shiny-armor-trims])
- [`Shrimp's Distinct Potions`][distinct-potions]: 1.1
- [`Shiny End Crystals`](https://modrinth.com/resourcepack/shiny-end-crystals):
  1.0
- [`Simple Grass Flowers`][simple-grass-flowers]: 1.9.2
- [`Spryzeen's Knight Armor`][knight-armor]: 1.8
- [`Taiga Painting`](https://modrinth.com/resourcepack/taiga-painting): 1.0
- [`Torches Reimagined`](https://modrinth.com/resourcepack/torches-reimagined):
  1.3.1
- [`Varied Pumpkins`](https://modrinth.com/resourcepack/varied-pumpkins): 1.2
- `Visual Overhaul (mod) built-in resource packs`
  - `visualoverhaul/rounddiscs`
  - `visualoverhaul/fancyfurnace`
  - `visualoverhaul/nobrewingbottles`
- [`xali's Enchanted Books`][enchanted-books]: 0.13.0

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

<!-- prettier-ignore-->
> [!NOTE]
> `${path_to_this_repo}` is the absolute path to this repository.

### Compressed Backup

Run the following command:

```bash
tar -I 'gzip -9' -cvf survival-ultra-vanilla-bkp.tar.gz backup
```

[jdk-temurin]: https://projects.eclipse.org/projects/adoptium.temurin
[jdk-temurin-sdkman]: https://sdkman.io/jdks/tem
[packwiz-installer-bootstrap]: https://github.com/packwiz/packwiz-installer-bootstrap
[packwiz-installer-bootstrap-version]: https://github.com/packwiz/packwiz-installer-bootstrap/releases/tag/v0.0.3
[fast-async-world-save]: https://www.curseforge.com/minecraft/mc-mods/fast-async-world-save-forge-fabric
[limited-chunk-loading]: https://www.curseforge.com/minecraft/mc-mods/limited-chunkloading
[server-performance]: https://www.curseforge.com/minecraft/mc-mods/smooth-chunk-save
[hotbar-keys-repo]: https://github.com/Hdoc1509/hotbar-keys
[hotbar-keys-branch]: https://github.com/Hdoc1509/hotbar-keys/tree/1.21
[hotbar-keys-commit]: https://github.com/Hdoc1509/hotbar-keys/commit/a036131859730765908871ccae3d6756ae878d54
[paginated-advancements]: https://modrinth.com/mod/paginatedadvancements
[text-formatting]: https://modrinth.com/mod/text-formatting-everywhere
[better-enchanting-table]: https://modrinth.com/resourcepack/better-enchanting-table
[creepers-reimagined]: https://www.curseforge.com/minecraft/texture-packs/creepers-reimagined
[default-dark-mode-expansion]: https://modrinth.com/resourcepack/default-dark-mode-expansion
[enchanting-table-magic-circle]: https://modrinth.com/resourcepack/enchanting-table-magic-circle
[enhanced-item-frame]: https://www.curseforge.com/minecraft/texture-packs/enhanced-item-frame
[fishing-hook-bobber]: https://modrinth.com/resourcepack/fishing-hook-bobber-3d
[human-era-villagers]: https://modrinth.com/resourcepack/human-era-villagers-illagers
[hunger-preview]: https://www.curseforge.com/minecraft/texture-packs/hunger-preview
[minecarts-with-wheels]: https://modrinth.com/resourcepack/minecarts-with-wheels
[ore-glint]: https://modrinth.com/resourcepack/spryzeens-ore-glint
[recolourful-containers]: (https://modrinth.com/resourcepack/spryzeens-ore-glint)
[shiny-armor-trims]: https://www.curseforge.com/minecraft/texture-packs/xxvis-shiny-armor-trims
[distinct-potions]: https://modrinth.com/resourcepack/shrimps-distinct-potions
[simple-grass-flowers]: https://modrinth.com/resourcepack/simple-grass-flowers
[knight-armor]: https://modrinth.com/resourcepack/spryzeens-knight-armor
[enchanted-books]: https://modrinth.com/resourcepack/xalis-enchanted-books
