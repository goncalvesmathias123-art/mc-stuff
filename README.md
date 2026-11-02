# EPCW Interactive updates

## Latest: version 2.1.3

[Download the 2.1.3 installer](https://raw.githubusercontent.com/goncalvesmathias123-art/mc-stuff/v2.1.3/installers/EPCW-Interactive-2.1.3-Setup.exe).

Use **Check for updates → Download → Restart & install**. Close both games before installation. Older-host launchers require one manual migration installation.

### Released draft changes

- Darker, scarier lighting with dim path lights and stronger shadows.
- Larger continuous-sculpt four-legged creature, 1.85x the original size, with a low hunched body and carved, pitted pumpkin head.
- Surface swimming circles nearby and follows player progress, using reachable local water routes instead of disappearing on long detours. Head and back remain above water.
- "I CAN'T TOUCH THE WATER" at the top centre, with the level counter directly underneath.
- Bottom-left control hints removed.

Keeps 100 levels with 50 jumps each, wide mixed-size platforms, angular/straight routes, 42-metre rooms, flying crows, updated water/tiles, two-second full-screen catch static, saves and next-room tunnels. Parkour Paridise 2 and original launcher mappings/TikFinity/overlay controls remain. Old Minecraft Water Parkour and Lava Rush remain removed.

### Validation

Passed 6,650 core checks, swimming orbit/follow tests, near-instant chase tests, all 15 launcher tests, browser controls/mappings and real launcher-to-exported-game authenticated events on Linux. During an 84.98 m sprint, the monster stayed within 8.73 m; near-wall patrol stayed within 9.50 m. The final export was rendered and inspected. All six sculpted mesh assets are checked in the installer. Redundant shadow-only copies were removed while preserving visible geometry.

Jump physics/course geometry are unchanged from 2.1.2, whose 5,000 jumps and 100 tunnels passed traversal. Native Windows installation, human balancing and performance on the user's machine remain untested. These are original procedural development visuals.

Signed metadata and installer size/SHA-256 verification retain the existing trusted key. No private keys, credentials or personal settings are published. Older installers and tags are retained.
