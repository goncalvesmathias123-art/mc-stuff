# EPCW Interactive updates

## Latest: 2.2.14

Choose **Check for updates → Download → Restart & install**. Close both games first. Supports unchanged 2.2.3 through 2.2.13; older apps receive the 2.2.3 migration first.

DON'T TOUCH THE WATER now has a separate green-and-gold controls panel in the same launcher, independent gift mappings, game/level status, gift enable/pause, countdown and play tests. TikFinity gifts route to the selected game. Water actions include +1, -1, +5, -5, reset in 60 seconds, save from reset, restart level, push, splash, monster chase, freeze, speed boost, low gravity and random obstacle. Each completed combo triggers once, regardless of repeat count.

New water profiles inherit configured Parkour gifts, or use the six preset gifts if none are configured. Profiles save independently; switching games pauses gift actions. The reset countdown continues through level changes, returns to level one when it expires, and can be canceled by save. The countdown is also available to the existing read-only LIVE Studio overlay.

Validation: 12 packaged launcher/backend/standalone/updater/overlay tests passed. Ten game action checks, twelve monster recovery checks and thirteen pebble-trip checks passed in the packaged game. An end-to-end simulated gift reached the real packaged game and advanced 20 to 25 exactly once; reset and save succeeded through the authenticated local API. UI preview reviewed and tested in-browser. Staged upgrades from 2.2.3 and 2.2.13 passed. Real TikFinity LIVE reception and live installation remain untested.

Existing jumps, monsters and scenery remain. Settings and previous installations are preserved. No private key or user data is included.
