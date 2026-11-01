# EPCW Interactive updates

## One-time update-host migration: version 2.0.5

[Download the migration installer](https://github.com/goncalvesmathias123-art/mc-stuff/releases/download/v2.0.5/EPCW-Interactive-2.0.5-Migration-Setup.exe).

Close EPCW Interactive, Minecraft and DON'T TOUCH THE WATER, then run the installer once. It installs the new launcher version and moves future update checks to this repository. Existing launcher settings, Parkour mappings and game saves are preserved. Older launcher versions still point to the previous update host and cannot discover this migration automatically.

After installing 2.0.5, use **Check for updates → Download → Restart & install** for future releases. The launcher checks signed metadata in `updates/parkour-stable.json`, verifies the installer size and SHA-256, and only then allows installation. This migration retains the existing replacement public signing key. No private keys, credentials or personal settings are published here.

## Included games

- **Parkour Paridise 2**: existing Minecraft integration, saved gift mappings, TikFinity, Play Test and LIVE Studio overlay. Requires your existing Modrinth Fabric 26.2 profile and Parkour Paradise 2 map.
- **DON'T TOUCH THE WATER**: bundled standalone game in enormous enclosed flooded rooms, approximately 76 metres wide with 14-metre ceilings. Includes dark fog, hanging lights, 100 courses, exactly 25 jumps per course and 6-foot exit tunnels. The player walks/runs/jumps on water while the monster swims below. There is no top-right gift guide. Minecraft is not required for this game.

The previous Minecraft Water Parkour and Lava Rush remain removed.

## Validation and limitations

The launcher passed 15 tests and browser card/mapping checks. The indoor game previously passed 3,428 core checks, automated traversal of 2,500 jumps and 100 tunnels, and launcher-to-exported-game tests on Linux. Game layouts, save IDs and the bundled game files are unchanged by this hosting migration. Native Windows installer execution and human game balancing remain untested. The standalone game is a development build.
