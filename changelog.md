## [1.1.3] - 2026-08-08

### Fixed

- Mod now loads properly, again

### Changed

- Bundled jar (Fabric/Forge/NeoForge/Quilt) now only targets the latest release. Fabric's resource loader can't resolve `pack.mcmeta` overlays for mod-provided resource packs, so one jar can't support multiple version-specific texture sets.
- On older versions where the mod jar isn't available, use the standalone datapack/resourcepack zips directly, or load them with a datapack loader like [Simple Datapacks](https://modrinth.com/mod/simple-datapacks) or [Datapack Injector](https://modrinth.com/mod/datapack-injector). Both still support the full version range via overlays.



## [1.1.2] - 2026-07-14

### Added

- 26.1 and 26.2 support

## [1.1.1] - 2026-03-16

### Fixed

- Mod now loads properly for all modloaders

## [1.1.0] - 2025-12-29

### Added

- Nautilus Armor
- Spear
- General progression advancements
- Automatically unlock recipes

### Changed

- Crafting an item longer gives the diamond tier as the base, preventing smithing table upgrade
- Prettier `pack.mcmeta`
- Horse Armor now has all its required fields for the `equippable` component

### Fixed

- No longer gives the "Cover Me with Diamonds" achievement when crafting a piece of armor
- Prevent smithing table upgrade for custom armor

## [1.0.1] - 2025-12-23

### Fixed

- Incorrect base attribute configuration on custom tools and armor that caused higher effective stats than intended
- Backend change: mod now follows proper semantic versioning format

## [1.0.0] - 2025-12-23

### Added

- Initial release

## [0.0.0] - YYYY-MM-DD

### Added

### Changed

### Removed

### Fixed
