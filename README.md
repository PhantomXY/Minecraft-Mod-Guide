# Minecraft-Mod-Guide
A Minecraft Java Fabric 1.19.1 Mod Performance Guide

⚠-Doesn't work on latest version at the moment.

---

## Prerequisites:
* Minecraft launcher: Either [official](https://www.minecraft.net/en-us) version or [Sklauncher](https://skmedix.pl/sklauncher/downloads).
 
* [Java](https://download.bell-sw.com/java/8u333+2/bellsoft-jre8u333+2-windows-amd64-full.msi) version thats is supported. 

* [Fabric](https://fabricmc.net/use/installer/) Loader so the mods will work.

---

### Framework / Libraries

* [Balm](https://www.curseforge.com/minecraft/mc-mods/balm-fabric/files)
  >Abstraction Layer for Blay's multiplatform mods.
* [CIT Resewn](https://www.curseforge.com/minecraft/mc-mods/cit-resewn/files)
  >MCPatcher's CIT re-written outside of optifine as a standalone mod.
* [Cloth API](https://www.curseforge.com/minecraft/mc-mods/cloth-api/files)
  >Cloth API is a generalized api.
* [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config/files)
  >Cloth Config API is a config screen api. 
* [Continuity](https://www.curseforge.com/minecraft/mc-mods/continuity/files)
  >Modern APIs to allow for the most efficient connected textures experience possible.
  >(Continuity will not work without the Indium mod if Sodium is installed.)
* [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api/files)
  >Core library for the most common hooks and intercompatibility measures utilized by mods using the Fabric toolchain.
* [Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin/files)
  >Enables usage of the Kotlin programming language for Fabric mods.
* [Mod Menu](https://www.curseforge.com/minecraft/mc-mods/modmenu/files)  
  >Adds a screen for viewing a list of installed mods.

---

### Performance

* [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps/files)
  >Clumps groups XP orbs together into a single entity to reduce lag.
* [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader/files)
  >Accelerates asset loading system by caching all of its content for a much faster game load.
* [Dynamic FPS](https://www.curseforge.com/minecraft/mc-mods/dynamic-fps/files)
  >Reduces the speed at which minecraft renders when it's not focused.
* [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling/files)
  >Skip rendering Block/Entities that are not visible.
* [FastChest](https://github.com/FakeDomi/FastChest/releases)
  >Removing dynamic models from chests and making them render as static chunk geometry.
* [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric/files)
  >Reduces the memory usage of Minecraft in a few different ways.
* [ForgetMeChunk](https://www.curseforge.com/minecraft/mc-mods/forgetmechunk/files)
  >Prevents light map unloads on the client, this eliminates the fps drops caused by crossing certain chunk borders.
* [Indium](https://www.curseforge.com/minecraft/mc-mods/indium/files)
  >Rendering optimisation mod for [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium/files).
* [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu/files)
  >Defers unnecessary initialization work so that it is only performed if required.
* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium/files) 
  >Improve a number of systems (game physics, mob AI, block ticking, etc) without changing any behavior.
* [MemoryLeakFix](https://www.curseforge.com/minecraft/mc-mods/memoryleakfix/files)
  >Fixes multiple memory leaks in minecraft.
* [MoreCulling](https://www.curseforge.com/minecraft/mc-mods/moreculling/files)
  >Multiple types of culling are handled in order to improve performance.
  >(Culling is when you don't render things that the player can't see, to improve performance)
* [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor/files)
  >Optimize lighting engine.
* [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium/files)
  >Greatly improves frame rates and stuttering while fixing many graphical issues.
* [Sodium Extra](https://www.curseforge.com/minecraft/mc-mods/sodium-extra/files)
  >Visual bug fixes and other performance options that are not yet available on Sodium.
* [Sodium Options](https://www.curseforge.com/minecraft/mc-mods/reeses-sodium-options/files)
  >Replaces Sodium's Options Screen with intention of improving UX.

---

### Quality of Life

* [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin/files)
  >Adds food value information and visualization of saturation and exhaustion to the HUD.
* [BetterF3](https://www.curseforge.com/minecraft/mc-mods/betterf3/files)
  >Replaces Minecraft's original debug HUD with a highly customizable, more human-readable HUD.
* [LambDynamicLights](https://www.curseforge.com/minecraft/mc-mods/lambdynamiclights/files)
  >Adds dynamic lights to the game.
* [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes/files)
  >Improves crashes in Minecraft.
* [Zoomify](https://www.curseforge.com/minecraft/mc-mods/zoomify/files)
  >Zoom with infinite customizability.
* [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap/files)
  >Adds a self-writing minimap.
* [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map/files)
  >Adds a self-writing fullscreen map.

---

### [More Minecraft Mods](https://github.com/Code-Moss/Sexycraft-Plus)

---
