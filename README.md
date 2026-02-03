# hunt-showdown-configs
Configuration files and scripts for Hunt: Showdown 1896 - optimized game settings and customizations

## What's in here

### NVPI-R/
NVIDIA Profile Inspector config files. You'll need [NVIDIA Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped) to import these.

- **Base-Profile.nip** - Global driver settings (affects all games)
- **Hunt-Showdown.nip** - Game-specific profile for Hunt: Showdown

These profiles tweak things like pre-rendered frames, sharpening, DLSS settings, and v-sync behavior for better performance and lower input lag.

### Root files
- **attributes.xml** - In-game settings, keybinds, weapon skins, and UI preferences
- **autoexec.cfg** - Console commands that run on game launch

## How to use

**NVIDIA profiles:**
1. Download [NVIDIA Profile Inspector Revamped](https://github.com/xHybred/NvidiaProfileInspectorRevamped/releases)
2. Import the profiles from the NVPI-R folder
3. Restart your PC or driver for changes to take effect

**Game configs:**
- `attributes.xml` goes in `%LOCALAPPDATA%\Crytek\Hunt\user\profiles\default\`
- `autoexec.cfg` goes in your Hunt: Showdown install directory

## Warning

These are my personal settings. They might not work well for your hardware or preferences. Import at your own risk, especially the NVIDIA base profile since it affects all your games.
