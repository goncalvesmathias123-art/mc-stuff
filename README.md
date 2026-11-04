# EPCW Interactive 2.2.20

Monsters keep up across the full course with distance-based catch-up swimming. Obstacle-grid rasterization now checks cell centers to avoid unnecessarily closing water passages. Far-away unreachable goals approach the nearest reachable bank rather than treating the creature's current position as its destination. Close-range spacing and physical pebble trips remain.

Landing on a course's final checkpoint automatically advances one level. The player is placed on the next course's starting pad with its proper respawn point; the former completion code moved the player back to the previous exit after loading. Final platforms display NEXT LEVEL, or FINISH on level 100. Intermediate checkpoints still save progress and refill pebbles. Level 100 completion ends the game without an invalid level 101 load.

Validation: source full-course pursuit tests passed on levels 1, 50 and 100, including water attacks at the end. Sampled following distances in these tests stayed below 18 metres after the fix, compared with over 30 metres in the original level-one test. Packaged level-50 pursuit passed. Packaged checkpoint progression checks (22), creature spacing/shared targets (15), five actual-world pebble trips, freeze recovery (12), convex navigation (7), gift and +/-10 actions (15), crow push (11), and four updater tests passed. Staged upgrades from 2.2.3 and 2.2.19 passed. Level data, gifts and centered transparent overlay are unchanged. Human playthrough and live installation remain untested.

Close both games → Check for updates → Download → Restart & install.

Installer SHA256: 2e36eba59b488c5bb32d00ce6c898e95848d971c0c96e4a01189a061a35e53b4
