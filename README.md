# EPCW Interactive 2.2.18

Creatures now use different dry-player approach lanes and collision-aware spacing, with a preferred visual gap. Predictive avoidance includes side steps, retreat and movement from overlapping starts. Shared pebble visits yield to one creature before the next approaches the same impact; the first creature vacates the approach area. Both still visit pebbles physically and attack exposed players.

Added +10 and -10 level actions to the water-game event API, gift selector and play tests. Levels clamp to 1-100. Two new unassigned gift rows are added once when mapping space is available; choose their gifts in the controls.

The existing LIVE Studio countdown link now renders an animated SAVE! heading, bouncing seconds, a shrinking green-yellow bar and floating Watermelon Love art. The HTML, body and panel backgrounds are fully transparent. Reset activates it, save hides it, and expiry hides it. No blue panel or white image card. Copy the LIVE Studio Link again after installing and replace the source URL; use approximately 440x740 for the Link source.

Validation: packaged creature spacing and shared-target tests (15) passed, with measured dry spacing above 7.6 m in the test. Five actual-world pebble locations recorded one visit by each creature. Packaged two-creature trip (13), freeze recovery (12), game actions and +/-10 clamps (15), crow push (11), and lifecycle (13) checks passed. Eleven packaged launcher/backend/gift/overlay/updater tests passed. Browser preview confirmed +10/-10 operation, reset activation, save cancellation and computed alpha-zero page/panel backgrounds. Staged upgrades from 2.2.3 and 2.2.17 passed. Level-layout data is byte-identical to 2.2.17. Live TikFinity reception and live installation remain untested.

Close both games → Check for updates → Download → Restart & install.

Installer SHA256: acc44456a6596bbe02759bf69b08d1ff642d253d8c16ad397b476e17f61d2b3d
