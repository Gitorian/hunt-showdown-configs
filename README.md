# hunt-showdown-configs

My Hunt: Showdown config files and tweaks.

## Global (Windows & Linux)

**attributes.xml**  
Game settings, keybinds, loadout preferences. Goes in `\Hunt Showdown 1896\USER\Profiles\default\attributes.xml`

**autoexec.cfg**  
Console commands that execute on launch. Put it in your Hunt install folder.  
Modified version by DEFICHENT NOT FOUND.

## Windows

**NVPI-R/**  
NVIDIA profiles for [Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped). The base profile affects all games, Hunt-Showdown.nip is game-specific. Mostly focused on reducing input lag and dialing in DLSS/sharpening.

### Installing NVIDIA profiles

1. Grab [NVIDIA Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped/releases)
2. Import the .nip files
3. Restart for changes to apply

Base profile affects all games.

## Linux

**Hunt.ini**  
[vkBasalt](https://github.com/DadSchoorse/vkBasalt) config. Reshade shaders running through a Vulkan layer - works with Proton. Includes sharpening, color tweaks, and a custom crosshair.

### Setup

1. Install [Proton-GE](https://github.com/GloriousEggroll/proton-ge-custom) for better performance
2. Install [vkBasalt](https://github.com/DadSchoorse/vkBasalt) from your distro repos or build from source
3. Download [Reshade shaders](https://github.com/crosire/reshade-shaders)
4. Edit Hunt.ini and point the paths to your shader location
5. Launch Hunt with `ENABLE_VKBASALT=1 %command%` in Steam launch options

The crosshair offset is set for 1440p.
