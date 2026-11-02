# EPCW Interactive updates

## Latest: version 2.1.4

[Download the 2.1.4 installer](https://raw.githubusercontent.com/goncalvesmathias123-art/mc-stuff/v2.1.4/installers/EPCW-Interactive-2.1.4-Setup.exe).

Use **Check for updates → Download → Restart & install**. Close both games before installation. Older-host launchers require one manual migration installation.

### Attack fixes and Poolrooms

- Creature circles closer and returns to nearby open water after checkpoint respawns.
- Attacks stop at visible body contact and hold during the catch effect. Capped swept movement and attack-only player collision prevent rushing through the player.
- Touching water keeps pursuit active through jumps. Only a genuine dry landing clears that exposure; clean platform jumps are safe. Standing on the creature does not cancel an attack.
- Walls and pillars block attack sightlines; successful dry landings cancel chase momentum immediately.
- Pale square tiles, greenish water, tall round tiled pillars and misty indoor-pool lighting follow the Poolrooms reference. Pillars have real cylinder collision and creature navigation clearance.

Keeps 100 levels with 50 jumps each, mixed-size wide-gap routes, the large sculpted four-legged creature, flying crows, the stacked top-centre HUD, two-second catch static, saves and tunnels. Parkour Paridise 2 and original launcher mappings/TikFinity/overlay controls remain. No bottom-left control strip or top-right gift guide.

### Verification

Passed 6,751 core checks, all 5,000 actual jumps and 100 tunnels in the final Poolrooms scene, four contact-attack cases including water hopping and sprinting in both directions, dry-landing and wall tests, close-swimming tests, column navigation, 15 launcher tests, browser controls/mappings and final launcher-to-exported-game integration on Linux.

Contact tests caught hopping players while airborne and stopped at the enlarged model's contact range. During an 84.98 m sprint the creature stayed within 6.16 m; initial patrol stayed within 4.72 m. Course traversal keeps moving/timed platforms active and disables the creature for route feasibility.

Native Windows installation, human balancing and performance on the user's machine remain untested. Art is procedural development work. Signed metadata and installer size/SHA-256 verification retain the existing trusted key. No private keys, credentials or personal settings are published. Older versions are retained.
