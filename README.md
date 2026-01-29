# Unfiltered Space

A visual clarity mod for Space Engineers that removes camera-simulating post-processing effects for a cleaner, more natural view of space.

## Features

### Removed Effects
- **Lens Flares** - Disabled on all light sources (sun, beacons, spotlights, interior lights, thrusters, jetpacks, welders, grinders, headlamps)
- **Lens Dirt** - Replaced with a clean texture
- **Eye Adaptation** - Disabled auto-exposure that causes brightness fluctuation
- **Chromatic Aberration** - Removed color fringing effect
- **Vignette** - Removed screen edge darkening
- **Ambient Player Light** - Disabled the artificial light that follows players, even in pitch black shadows
- **Mie Scattering Glare** - Removed atmospheric glare on planets (Alien, EarthLike, Europa, Mars, Titan)

### Adjusted Settings
- Nebula-free skybox using the game's alternate stars-only background
- Reduced atmospheric envelopes around planets for a more realistic appearance from space
- Increased skybox brightness for more visible stars
- Tweaked sun and ambient lighting factors
- Removed clouds from Triton and Pertam
- Adjusted atmosphere heights and fog on various planets

## Installation

Subscribe on Steam Workshop or copy the mod folder to:
```
%appdata%\SpaceEngineers\Mods\
```
## Compatibility

This mod overrides parts of the default environment, flare, and planet generator definitions. It has been carefully written to only change what absolutely needs to be changed and nothing else.

## Load Order

Mods loaded later take priority when multiple mods modify the same files.

- To preserve this mod's changes, load it **after** other environment/planet mods.
- To let another mod's visuals take priority, load this mod **before** it.

## License

This mod is licensed under the [GNU Affero General Public License v3.0](LICENSE).
