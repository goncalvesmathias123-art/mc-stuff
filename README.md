# EPCW Interactive 2.2.16

Gold Boxing Glove → Crow push is added to the water game's galaxy controls. The vector glove icon is bundled in the launcher; exact boxing-glove name aliases resolve received LIVE IDs without hard-coded numeric IDs or an assumed coin price. The new mapping is added once to existing water profiles when mapping space is available. Other mappings are retained.

The push action now spawns a procedural crow with flapping feathered wings, eyes, beak, tail and synthesized caw. It approaches, locks its attack position and can be dodged. Physical contact applies a decaying shove toward the nearest open platform edge; it does not teleport the player. Each bird strikes once. Up to three active birds, pause handling, lifetime limits, level-change cleanup and cleared respawn momentum prevent lingering attacks.

Validation: packaged crow hit/shove/dodge/pause/cleanup checks (11), monster recovery checks (12), pebble trips (13), gift actions (10), and route/physics checks (138641 including 240 jumps) passed. Ten launcher/preset/gift/updater tests passed; final preset/gift subset passed after adding exact alternate names. In-engine crow preview and launcher gift mapping reviewed. Staged upgrades from 2.2.3 and 2.2.15 passed before alias-only refinement; final 2.2.15 staging passed. Real TikFinity LIVE reception and live installation untested.

Close both games → Check for updates → Download → Restart & install.

Installer SHA256: 4f4b0d6a1e4c6dc99bd7511540f6dc19317bec7eba2806ad0d5e197c30e171dc
