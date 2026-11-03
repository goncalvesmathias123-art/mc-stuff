# EPCW Interactive updates

## Latest: 2.2.13

Choose **Check for updates → Download → Restart & install**. Close both games first. Supports unchanged 2.2.3 through 2.2.12; older apps receive the 2.2.3 migration first.

Fixes a reproduced monster freeze at wall contact and corners. Shape sweeps could ignore a touching wall because the clearance probe already overlapped it. Corrected the probe start and added a wall ray check. Both creatures can refresh stale obstacle maps and commit to clear recovery detours, including backing away. Net-progress detection also catches corner oscillation. Moving-platform exclusion areas are anchored at their original positions.

Pebbles still require a physical visit before returning toward the player. Wider jump layouts and scenery are unchanged.

Validation: the late-obstacle corner regression failed on 2.2.12 and passes on 2.2.13 for both variants and chase/pebble cases (12 checks). Packaged long pebble detour (7), actual two-creature pebble trips (13), pillar pursuit (6), lifecycle (13), detail/transition (7) and updater tests (7) passed. Staged upgrades from 2.2.3 and 2.2.12 passed. Human playthrough and live installation remain untested.

Settings and previous installations are preserved. No private key or user data is included.
