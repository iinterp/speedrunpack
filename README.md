# SpeedrunPack

Contains all mods that are verifiable on [speedrun.com](https://www.speedrun.com/mc) across most modern Minecraft versions.

Some mods are only usable in certain categories or circumstances, they will be disabled by default. The version mod lists note these cases.

---

<details><summary>Mod Overview</summary>

<details><summary>Speedrun Mods</summary>

## [SpeedRunIGT](https://redlime.github.io/SpeedRunIGT/)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Tracks your In-Game Time (IGT) and Real Time Attack (RTA) while you play. RTA is the total time since the timer started, IGT is this time without pauses.

You can change the settings and customize the timer from the options menu ender pearl icon.

## [Atum](https://github.com/VoidXWalker/Atum)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Auto creates a new world upon leaving one. To stop resetting, press `Stop Resets & Quit` from the Options menu.

Can be started by clicking the gold boots icon on the main menu, shift clicking the icon opens the Atum settings, where you can change difficulty and the world seed.

## [World Preview](https://github.com/VoidXWalker/WorldPreview)
`1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Shows a preview of the world as it is being created.

Has hotkeys to leave the preview, freeze the preview and change the chunkmap location, all customizable in control settings.

## [StandardSettings](https://github.com/KingContaria/StandardSettings)
`1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Defaults settings to a standard set by the player when creating a new world. It's designed to replace the much slower, much laggier and more inconsistent solution of doing it by macro.

Must be set up using the mod config, learn more [here](https://github.com/KingContaria/StandardSettings#how-can-i-edit-my-standardsettings).

*Disabled by default*

## [FastReset](https://github.com/jan-leila/FastReset)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Adds a new button to the pause menu *quit.menu*, which leaves the current world without saving, making resets faster.

The button location can be changed from the options menu.

</details>

<details><summary>Set Seed Only Mods</summary>

## [set-spawn-mod](https://github.com/Minecraft-Java-Edition-Speedrunning/mcsr-set-spawn-1.16.1)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Set your spawnpoint to specified coordinates during set seed runs.

*Disabled by default*

## [ChunkCacher](https://github.com/Minecraft-Java-Edition-Speedrunning/mcsr-chunkcacher-1.16-1.17.1)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Caches chunks up to before features stage for set seed.

*Disabled by default*

</details>

<details><summary>Performance Mods</summary>

## [Sodium](https://modrinth.com/mod/sodium) [[2]](https://github.com/Minecraft-Java-Edition-Speedrunning/mcsr-sodium-1.16.1)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2`

Greatly improves frame rates and stuttering while fixing many graphical issues.

`1.18.2` `1.17.1` `1.16.5` `1.16.1` `1.15.2`\
Adds a new option in the video settings menu to enable Planar Fog for NVIDIA GPUs, which allows you to see further through fog at the edges of your screen for parity with AMD GPUs.

`1.16.1`\
Restores the vanilla pause video settings menu and allows the in-game brightness slider to be set to a max of 500%. The original Sodium menu can be accessed from the main menu.

## [Lithium](https://modrinth.com/mod/lithium) [**[2]**](https://github.com/mrmangohands/lithium-fabric)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2`

Lithium is a modern, general-purpose optimization mod for Minecraft which works to improve a number of systems (game physics, mob AI, block ticking, etc) with the goal of not changing any vanilla mechanics.

## [Starlight](https://modrinth.com/mod/starlight) [**[2]**](https://github.com/Minecraft-Java-Edition-Speedrunning/mcsr-starlight-1.16-1.16.5)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2`

Rewrites the light engine to fix lighting performance and lighting errors.

Usually faster than Phosphor

*Incompatible with Phosphor*

## [Phosphor](https://modrinth.com/mod/phosphor) [[2]](https://github.com/mrmangohands/phosphor-fabric)
`1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1`

Optimizes the Minecraft lighting engine.

Usually slower than Starlight

*Incompatible with Starlight*\
*Disabled by default*

## [OptiFabric](https://github.com/Sjouwer/OptiFabric-1.14.4-Updated)
`1.14.4`

Allows OptiFine to function on Fabric.

Only enable if you add OptiFine. OptiFine is incompatible with LazyStronghold, LegacyPlanarFog & WorldPreview.

*Disabled by default.*

## [SleepBackground](https://github.com/RedLime/SleepBackground)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Reduces FPS cap while Minecraft is in the background.

Settings can be changed from the config file.

## [AntiResourceReload](https://github.com/wurgo/antiresourcereload)
`1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Caches datapack and server resources to make world generation faster.

## [Krypton](https://modrinth.com/mod/krypton) [**[2]**](https://github.com/mrmangohands/krypton)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Optimizes the Minecraft memory stack.

## [LazyDFU](https://modrinth.com/mod/lazydfu)
`1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

An optimization mod for Minecraft that defers unnecessary initialization work so that it is only performed if required.

## [AntiGone](https://github.com/Minecraft-Java-Edition-Speedrunning/mcsr-antigone-1.16.1)
`1.16.1`

This mod fixes a rare server thread crash involving an interaction with striders and chicken jockeys.

## [BiomeThreadLocalFix](https://github.com/RedLime/BiomeThreadLocalFix)
`1.20.4` `1.19.4` `1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5`

Fixes a memory leak

## [LazyStronghold](https://github.com/Gregor0410/LazyStronghold)
`1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Lazy evaluation of stronghold generation combined with a multi threading optimization for faster resets in Minecraft speedruns.


## [Voyager](https://github.com/modmuss50/Voyager)
`1.16.5` `1.16.1` `1.15.2` `1.14.4`

Fixes a rare CME (ConcurrentModificationException) when using Java 11+.


</details>

<details><summary>Misc Mods</summary>

## [Force Port](https://github.com/DuncanRuns/Force-Port-Mod)
`1.19.2` `1.18.2` `1.18.1` `1.17.1` `1.16.5` `1.16.1` `1.15.2` `1.14.4`

Makes opening to LAN always open to port 25565, for easier multiplayer.

Additionally, it increases the player limit of an open to LAN world to 20 rather than 8.

## [Extra-Options](https://github.com/VoidXWalker/extra-options)
`1.16.1` `1.15.2` `1.14.4`

Adds the 1.17 options of a monochrome logo, reduced distortion effects and reduced FOV effects.

**Allowed if medically necessary only, with permission from the moderation team *before* submission.**

*Disabled by default.*

</details>

Versions before 1.14 use [Fabric Legacy](https://legacyfabric.net/downloads.html), which Modrinth can't support. :(

You can see the pre-1.14 modlist [here](https://mods.tildejustin.dev), or download a pre-made instance for MultiMC/Prism Launcher [here](https://github.com/Minecraft-Java-Edition-Speedrunning/legacy-fabric-instance-generator/releases).

</details>

## Installation

<details><summary>Modrinth App</summary>

### 1. Navigate to browse and search for SpeedrunPack
Click SpeedrunPack and switch to the Versions tab

### 2. Download the version you want to play
Navigate back to the library tab

</details>

<details><summary>Prism Launcher & MultiMC</summary>

### 1. Add Instance > Modrinth > Search for SpeedrunPack
Select the version you want to play and then select OK

### 2. Optional mods
Enable optional mods from the Mods tab

Only enable mods that will be legal for your use case
</details>

<details><summary>ATLauncher</summary>

### 1. Search for SpeedrunPack in ATLauncher and click New Instance
The search can be found under Packs > Modrinth

### 2. Select the version you want and click install
Name the instance anything you like

### 3. Select any optional mods you want to enable and click install
Don't click recommended mods, only select mods that will be legal for your use case

</details>

## Other Resources

**[Ninjabrain Bot](https://github.com/Ninjabrain1/Ninjabrain-Bot)** - An accurate stronghold calculator for Minecraft speedrunning

**[MCSR Ranked](https://modrinth.com/mod/mcsr-ranked)** - Ranked speedrunning mod

**[Bastion Practice Map](https://github.com/LlamaPag/bastion/releases/latest)** by LLamaPag

**[Portal Practice Map](https://github.com/Semperzz/Portal-Practice/releases/latest)** by ItzToxic & Semperzz

**[End Practice Map](https://github.com/ryguy2k4/ryguy2k4endpractice/releases/latest)** by ryguy2k4

& more at **[MinecraftSpeedrunning.com](https://www.minecraftspeedrunning.com/public-resources)**

---

> This is an unofficial source and may not always be up-to-date. The official source for legal mods can be found [here](https://mods.tildejustin.dev).
