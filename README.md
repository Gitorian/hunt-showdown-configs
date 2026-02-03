# hunt-showdown-configs

My Hunt: Showdown config files and NVIDIA driver tweaks.

## Files

**NVPI-R/**  
NVIDIA profiles for [Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped). The base profile affects all games, Hunt-Showdown.nip is game-specific. Mostly focused on reducing input lag and dialing in DLSS/sharpening.

**attributes.xml**  
Game settings, keybinds, loadout preferences. Goes in `%LOCALAPPDATA%\Crytek\Hunt\user\profiles\default\`

**autoexec.cfg**  
Console commands that execute on launch. Put it in your Hunt install folder.  
Modified version by DEFICHENT NOT FOUND.

## Installing NVIDIA profiles

1. Grab [NVIDIA Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped/releases)
2. Import the .nip files
3. Restart for changes to apply

Fair warning: the base profile changes global driver settings. If you don't know what pre-rendered frames or v-sync tear control do, maybe skip that one.

## Notes

These work for my setup. Your mileage may vary depending on hardware and what you're used to.
