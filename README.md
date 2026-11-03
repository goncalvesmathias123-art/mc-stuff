# EPCW Interactive updates

## Latest: 2.2.9

Choose **Check for updates → Download → Restart & install**. Close both games first. Supports unchanged versions 2.2.3–2.2.8; older apps receive the 2.2.3 migration first.

- Pebbles distract nearby creatures for 1.5 seconds, then all immediately retarget the player.
- Removes post-pebble circling, roaming and return-state targets.
- Creatures continue tracking dry players to the water edge; a catch still requires water exposure.
- Uses direct body-clearance steering, obstacle paths and short local recovery, with no stale-waypoint speed cap on a clear direct route.
- Retains the reference-look 2.2.8 visuals, three creatures, levels and obstacles.

Validation: 50 monster regressions, 42 direct-pursuit checks, 9 actual-thrown-pebble group checks, 6 pillar-path checks and 17 lifecycle checks passed in source. The 42/9/6 checks also passed using the packaged game. Seven updater/standalone tests passed. Staged upgrades from 2.2.3 and 2.2.8, and intermediate-version compatibility verification, passed. Live installation and human playthrough remain untested.

Settings and previous installations are preserved. No private key or user data is included.
