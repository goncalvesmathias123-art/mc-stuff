# EPCW Interactive 2.2.25

Fixes God Kit delivery when a large-stack mod causes Minecraft's /give command to overflow maxStackSize * 100 to a negative limit. The kit now parses and validates all item specifications against the running server's registries before directly inserting them into the recipient's inventory. Remaining items are dropped beside the player with immediate pickup and ownership targeting. The inventory menu is synchronized after delivery. Failure to deliver an overflow item propagates instead of being reported as success; the launcher also requires an explicit delivery confirmation.

The kit remains enchanted Netherite armor, sword, two pickaxes, shovel, bow, 24 enchanted golden apples, 16 ender pearls and 64 arrows. Existing equipment is preserved. Gift mappings, the 745-entry US catalog, world creation, water game and overlay remain unchanged.

Validation: a Java delivery regression reproduced Integer.MAX_VALUE * 100 == -100 and verified all 12 stacks / 113 items through empty, full and partial inventory cases, overflow targeting and pickup, inventory synchronization, and failure propagation. Exact apple and pearl quantities were checked. All 23 launcher tests and six packaged tests passed. Staged upgrades from 2.2.23 and 2.2.24 passed. Tests used simulated inventories; live delivery with the installed fix remains unverified.

Fully close Minecraft -> Download update -> Restart & install -> Minecraft Chat Chunk -> Resume last world. Launching through the launcher copies the corrected bridge into the Minecraft profile while preserving the previous bridge as a backup. Then use the God Kit row's play-test button or a mapped Boxing Glove gift.

Installer SHA256: f5c4bb2a28015dfb9c9b625915d93ff4da4e93e88e220d720e4262e8bffed5dc
