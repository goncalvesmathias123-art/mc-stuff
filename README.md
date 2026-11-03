# EPCW Interactive updates

## Latest: 2.2.7

Choose **Check for updates → Download → Restart & install**. Close both games first. Supports unchanged 2.2.3–2.2.6 installations; older apps receive the 2.2.3 signing migration first.

- Fixes a reproduced post-pebble freeze when local patrol destinations are unreachable, with fallback roaming and stalled-movement recovery. Navigation no longer treats hazard trigger Areas as physical walls.
- Three visually distinct creatures with horns, reflective eyes, dorsal spines and water wakes. Pebbles, pause, catch and respawn control the whole group.
- Positional growls, worn beveled platforms, waterline staining, pillar markings, warning lamps, floating wreckage and cooler horror lighting.
- Retains 100 levels, 80 jumps, 15 pillars and the existing varied obstacles.

Validation: the old blocked-patrol regression moved 0 metres, while the new build moved about 13 metres in the same interval. Five full-level post-pebble movement cases passed; 17 group lifecycle checks passed in source and the packaged game. Existing 49 monster checks, 12 navigation checks, 138,641 route checks and 240 physics jumps passed. All 60 packed checksums and 10 patch contents verified; staged upgrades from four supported versions and seven updater/standalone tests passed. In-engine visuals reviewed. Human playthrough and live installation remain untested.

Settings and previous installations are preserved. No private key or user data is included.
