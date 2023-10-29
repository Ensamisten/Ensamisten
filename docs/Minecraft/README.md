
# Java Modding Documentation for Minecraft

## Mod Loaders
> :memo:
Mod Loader is a generic term for a software component that facilitates the loading and management of mods in video games. It acts as an intermediary between the game engine and the individual mods, allowing multiple mods to be used simultaneously without conflicts. Mod Loaders are often used in games that have an active modding community and provide an API for mod developers to hook into the game's code and alter its behavior.

### Forge
> :memo:

### ModLoader
> :memo:

### Fabric
> :memo:

## File Structure

**Replace minecraft with your modid.**


- Blockstates: assets/minecraft/blockstates
> Contains JSON files that define the model variants and states for blocks.
- Fonts: assets/minecraft/font/
> Contains TrueType font files for in-game text rendering.
- Icons: assets/minecraft/icons/
> Contains various icons used in the game's user interface. 
- Lang: assets/minecraft/lang/
> Contains JSON files that define the game's text translations for different languages.
- Models: assets/minecraft/models/
> Contains JSON files that define the 3D models for blocks and items.
- Paintings: assets/minecraft/paintings/
> Contains images for the in-game paintings.
- Particles: assets/minecraft/particles/
> Contains JSON files that define particle effects.
- Shaders: assets/minecraft/shaders/
> Contains shaders used for rendering effects.
- Sounds: assets/minecraft/sounds/
> Contains sounds used in the game. Uses the "**.ogg**" file format.
- Textures: assets/minecraft/textures/
> Contains the main textures used for blocks, items, and other in-game elements.
  - Colormap: assets/minecraft/textures/colormap/
> Contains JSON files defining the color maps used for various biome-related features.
  - Color: assets/minecraft/textures/color/
> Contains JSON files that define the colors for specific features.
  - Effect: assets/minecraft/textures/effect/
> Contains images for various in-game effects.
  - Entity: assets/minecraft/textures/entity/
> Contains images for entities (mobs and creatures).
  - Environment: assets/minecraft/textures/environment/
> Contains images for sky, clouds, and other environmental textures.
  - Font: assets/minecraft/textures/font/
> Contains images for fonts used in the game's user interface.
  - Gui: assets/minecraft/textures/gui/
>  Contains images for graphical user interface elements.
  - Items: assets/minecraft/textures/items/
>  Contains images for item textures.
  - Map: assets/minecraft/textures/map/
> Contains images for maps and map-related textures.
  - Misc: assets/minecraft/textures/misc/
> Contains miscellaneous images used in the game.
  - Mob_effect: assets/minecraft/textures/mob_effect/
> Contains images for potion and status effect icons.
  - Painting: assets/minecraft/textures/painting/
> Contains images for paintings.
  - Particle: assets/minecraft/textures/particle/
>  Contains images for particle effects.
  - Terrain: assets/minecraft/textures/terrain/
> Contains images for terrain block textures.
  - Title: assets/minecraft/textures/title/
> Contains images for the game's title screen.
  - Underwater: assets/minecraft/textures/underwater/
> Contains images for underwater-related textures.
