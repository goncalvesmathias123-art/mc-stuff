# EPCW Interactive updates

## Latest: version 2.0.6

[Download the 2.0.6 installer](https://raw.githubusercontent.com/goncalvesmathias123-art/mc-stuff/v2.0.6/installers/EPCW-Interactive-2.0.6-Setup.exe).

If you already installed 2.0.5, use **Check for updates → Download → Restart & install**. Close the launcher and both games before installation. Older-host launchers need one manual installation to switch to this repository; future updates then work in-app. Existing Parkour mappings and level/checkpoint progress are preserved.

### Gameplay changes

- Dense short-range fog: see roughly the next two platforms.
- Lower, more controllable jumps with normal gravity, lower platforms and shorter gaps. Sinking platforms no longer weaken the jump at takeoff.
- The next room is already visible before you enter its six-foot tunnel. Crossing promotes that exact room without rebuilding it or moving the player.
- The monster walks upright with grounded collision, animated strides and obstacle-aware patrol/search paths. It responds to splashes.

Keeps the enormous enclosed flooded-room setting, 100 courses, 25 jumps per course, and no top-right gift guide. The standalone game requires no Minecraft. Parkour Paridise 2 remains in the launcher with its Minecraft gift mappings, TikFinity controls, Play Test and LIVE Studio overlay. The old Minecraft Water Parkour and Lava Rush remain removed.

### Verified updates

The launcher checks signed metadata at `updates/parkour-stable.json`, then verifies installer size and SHA-256 before allowing installation. The existing replacement signing key is retained; no private keys, credentials or personal settings are published here. Earlier installers and tags are retained.

### Validation and limits

Version 2.0.6 passed 3,634 core checks, automated traversal of all 2,500 jumps and 100 tunnels, 15 launcher tests, browser controls/mapping checks and launcher-to-exported-game tests on Linux. Core checks include actual walking patrols and grounding, escaping water with the lower jump, preloaded next-room visibility and continuity across the tunnel. The standalone game remains a development build. Human balance testing and native Windows installation/gameplay testing remain untested.
