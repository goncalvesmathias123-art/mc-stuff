# EPCW Interactive 2.2.23

New stream world creates a separate Minecraft Java 26.2 survival world with a cryptographically random seed and unique dated folder, then opens it through the existing Modrinth profile. Previous stream worlds remain intact. Resume last world reopens the latest generated save. A small auto-enabled datapack activates Chat Chunk controls on load; manual world creation and activation are no longer needed. Disabled chat blocks and gift mappings carry over. Close Minecraft before making a new world.

Chat Chunk now has five configurable gift actions. Netherite chunk, Lava chunk, Air chunk and Cobweb chunk each transform the existing terrain in the selected player's current chunk. These gift actions deliberately work independently of the chat block switches, so restricted chat blocks can be reserved for gifts. Choose which gifts trigger these four actions in the launcher.

Gold Boxing Glove / Boxing Glove is preset to God Kit in Chat Chunk. It gives enchanted Netherite helmet, chestplate, leggings and boots; sword; Silk Touch pickaxe; Fortune pickaxe; shovel; enchanted bow; 24 enchanted golden apples; 16 ender pearls; and 64 arrows. Armor and equipment are given as items, preserving existing equipment. Kit enchantments follow the reference using normal maximum enchantment levels. The water game's glove-to-crow mapping remains separate.

Validation: 21 launcher tests and nine packaged tests passed. Minecraft 26.2's own codecs and world-list reader accepted two generated worlds, their survival/normal settings, distinct seeds and names, all three noise-generated dimensions, and enabled control pack. Minecraft's ItemParser accepted all 12 God Kit stack specifications and enchantment components. Tests cover new-world versus resume behavior, saved settings, gift override of chat restrictions, all four chunk gifts, glove alias routing and duplicate-gift suppression. Browser preview verified world creation and gift controls. Staged upgrades from 2.2.21 and 2.2.22 passed. Water game PCK and transparent centered overlay are unchanged. Tests used isolated saves; a real TikTok LIVE and human Minecraft playthrough remain unverified.

Close both games -> Check for updates -> Download -> Restart & install. In Minecraft Chat Chunk, click New stream world, link TikFinity, and Enable chat & gifts.

Installer SHA256: 6258679cf06006b8fccd9f8f732b3c73d4167ba174ddf602c36b6da25318d35e
