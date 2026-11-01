# EPCW Interactive updates

## Latest: version 2.0.8

[Download the 2.0.8 installer](https://raw.githubusercontent.com/goncalvesmathias123-art/mc-stuff/v2.0.8/installers/EPCW-Interactive-2.0.8-Setup.exe).

If you already installed 2.0.5 or newer, use **Check for updates → Download → Restart & install**. Close the launcher and both games before installation. Older-host launchers need one manual installation to switch to this repository; future updates then work in-app. Existing Parkour mappings and level/checkpoint progress are preserved.

### Gameplay changes

- Reduced fog: see several platforms ahead, with dim shaded lamps along the route and restrained ambient lighting.
- Stronger original jump and running movement restored, with longer gaps and broad left/right route bends. Wall obstacles sit beside diagonal landing approaches.
- The next room is already visible before you enter its six-foot tunnel. Crossing promotes that exact room without rebuilding it or moving the player.
- The monster crawls at water level with animated limbs and obstacle-aware paths. A splash gives a 2-second reaction window, then triggers fast pursuit. Reaching a dry platform breaks the chase.

Keeps the enormous enclosed flooded-room setting, 100 courses, 25 jumps per course, and no top-right gift guide. The standalone game requires no Minecraft. Parkour Paridise 2 remains in the launcher with its Minecraft gift mappings, TikFinity controls, Play Test and LIVE Studio overlay. The old Minecraft Water Parkour and Lava Rush remain removed.

### Verified updates

The launcher checks signed metadata at `updates/parkour-stable.json`, then verifies installer size and SHA-256 before allowing installation. The existing replacement signing key is retained; no private keys, credentials or personal settings are published here. Earlier installers and tags are retained.

### Validation and limits

Version 2.0.8 passed 3,737 core checks, unchanged route geometry previously traversed through all 2,500 jumps and 100 tunnels in 2.0.7, 15 launcher tests, browser controls/mapping checks and launcher-to-exported-game tests on Linux. Core checks include water-level crawling, two-second splash delay, accelerated chase and dry-platform escape, substantial left/right turns on every route, preloaded next-room visibility and continuity across the tunnel. The standalone game remains a development build. Human balance testing and native Windows installation/gameplay testing remain untested.
