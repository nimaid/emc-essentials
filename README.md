# <img src="icon.png" height="20px" alt="EMC Essentials"/> EMC Essentials
## Modern vanilla Minecraft with ProjectE, plain and simple!

This pack aims to act as a simple pack for those wanting to use the ProjectE mod (a rewrite of the original Equivalent Exchange 2 mod) in modern Minecraft versions.

This pack includes common add-ons to extend the features of ProjectE, such as higher tier EMC generators, compact power flowers, and a tablet with a crafting table built in.

This pack aims to support the latest possible Minecraft version. Currently, this is version `1.20.1`, as ProjectE has not updated past this version yet.

## What Does EMC Mean? What is ProjectE?
The ProjectE mod (previously known as Equivalent Exchange) adds a version of alchemy to Minecraft. Almost every item in the game has an Energy-Matter Covalence (EMC) value. Common items like cobblestone have low EMC values like `1`, but rarer items such as diamonds have much higher values like `8192`. Items which are crafted have an EMC value equal to the sum of its ingredients.

This means that, through various means, all matter can be broken down into EMC points and then re-constructed into new matter with the same EMC value. So in theory, you can turn `8192` cobblestone blocks into `1` diamond gem. However, to do these transmutations, you will need special alchemical equipment.

### Energy Condenser
This special chest has a slot in the upper left that doesn't actually hold an item, but instead "learns" the item you try to place in it. Then, it will destroy all other items in the chest that have EMC, and will condense this EMC into the learned item. You can change the learned item whenever you want, but only 1 item can be learned at a time.

Later on, you can use these to receive EMC from adjacent blocks (like Energy Collectors or Antimatter Relays) instead of manually burning EMC from items.

### Philosopher's Stone
This can transmute blocks and valuable materials in a limited capacity. It can fire a projectile that randomly transmutes mobs. It is used to craft many higher-tier alchemical devices, and also comes with a built in portable crafting table.

### Transmutation Table
This is the first "general purpose" EMC device. It is a slab-like block that can be placed anywhere, even on walls. You can directly put items with an EMC value into the table, which will add it's EMC value to your personal EMC balance (shown at the top left of the screen). When you "burn" an item in the transmutation table for the first time, it will be "learned", and you will be able to pull that item out again if you have enough EMC.

The learned items and EMC balance are tied to your player character, not the physical table. When you learn an item on one table/tablet, you learn it on them all.

You can transfer EMC to another player using either a Klein Star or by giving them valuable items. To share your learned items, you will need to craft a Knowledge Sharing Book.

### Transmutation Tablet
This is just a portable (and much more expensive) version of the Transmutation Table.

### Arcane Tablet
This is an upgrade to the Transmutation Tablet that adds a 3x3 crafting grid. Now you can use JEI to automatically pull the items out of the tablet and then put them in the grid with only a single click.

## I want more EMC than I can gather!
You can also generate EMC from light using some additional devices:

### Energy Collector
These come in different tiers, the more expensive they are, the more EMC they produce. Collectors need to be fully illuminated to generate max EMC, although high-tier collectors produce enough of their own light to make external lights unnecessary. These can either be used alone to enrich fuels into higher value variants, or can be placed adjacent to EMC-collecting blocks such as Antimatter Relays, Energy Condensers, and EMC Links.

### Antimatter Relay
These come in different tiers, the more expensive they are, the more EMC they can transfer and the higher the EMC bonus they provide. These devices can operate alone to rip apart items into their raw EMC, or they can simply be used to transfer EMC between blocks. When EMC flows through a relay, an additional EMC bonus is added, meaning the best EMC generators always incorporate relays.

Generally, you want the relay tier to roughly match the collector tier. Undersized relays may not be able to keep up with the EMC produced, and oversized relays are often a waste of EMC that could be spent on additional or better collectors.

### EMC Link
These devices can receive EMC from collectors or relays and directly transfer it into your EMC balance! No more throwing chests filled with diamonds into your tablet, using these fully automates your EMC production!

They come in different tiers as well, make sure to match the tier of the collectors/relays used to avoid making an EMC bottleneck.

### Power Flowers
The natural structure that works out to be the "best" configuration for generating EMC is an EMC link at the center, 6 relays covering every face of the link, and then 18 collectors covering every face of the relays. This structure is known as a "Power Flower", and you can actually craft miniature (single block) versions of each tier! You will still need to supply all the requisite ingredients through the crafting recipe.

This allows you to quickly expand your EMC production by learning the power flower in a tablet and pulling out as many as you can. Place them all in a loaded chunk and wait until you have enough EMC to upgrade your flowers to the next tier.

## I want more EMC than God himself!
There are several ways to make your EMC production go to the moon. In vanilla Minecraft, I can't imagine how this would ever be useful, but still, nothing is stopping you but your own limited hubris!

### Watch of Flowing Time
This item is simply overpowered. It allows you to control the movements of the moon and the sun, in addition to allowing you to accelerate time in the local area around the watch. This means that plants grow faster, fire burns faster, and yes, EMC generates faster from power flowers as well.

Charge it with V, discharge with Shift+V. The more it is charged, the faster it will accelerate time. Press G to toggle the time acceleration effects, the watch will be gold when activated. Finally, you can right-click with the watch to control the moon and sun.

The effect stacks, and exponentially so. However, they only work if they are in your hotbar or offhand. Therefore, the maximum number of watches you could theoretically stack with a single player is 10. Using all 10 slots for fully charged watches makes a MkI power flower generate `16,422` EMC/s instead of its default `102` EMC/s.

### Dark Matter Pedestal
These can hold many of the alchemical devices ProjectE adds, often with special effects on the environment or nearby mobs. For EMC generation, all we care about is that it can hold a Watch of Flowing Time that accelerates time around it *without* the player being near. While they don't speed up time as much as they would in the player's inventory, the only limit to how many you can stack is the space you have to place pedestals. For each pedestal with a watch you place around your EMC farm, it will exponentially improve your EMC/s.

Simply place the pedestal, right-click with the watch to place it on the pedestal, and then right-click again to activate the pedestal.

### Miniature Sun
This is a very expensive item. However, if you place it on top of energy collectors (or below compact Power Flowers), it will multiply the EMC output by 10x. This of course stacks with time acceleration effects.

### The Final EMC Farm
A Final Power Flower sitting on a Miniature Sun with 8 activated Dark Matter Pedestals holding 8 Watches of Flowing Time generates **69.54 Quadrillion EMC/s**, which is so absurd I have absolutely no idea how you could even manage to use that much EMC that fast in vanilla.

---
---
## Mods Used
### New Features
- [ProjectE](https://www.curseforge.com/minecraft/mc-mods/projecte)
- [Project Expansion](https://www.curseforge.com/minecraft/mc-mods/project-expansion)
- [Arcane Tablet](https://www.curseforge.com/minecraft/mc-mods/arcane-tablet)
- [Rechiseled](https://www.curseforge.com/minecraft/mc-mods/rechiseled)

### Quality of Life
- [Custom Window Title](https://www.curseforge.com/minecraft/mc-mods/custom-window-title)
- [JEI](https://www.curseforge.com/minecraft/mc-mods/jei)
- [JER](https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer)
- [More Overlays Updated](https://www.curseforge.com/minecraft/mc-mods/more-overlays-updated)
- [Configured](https://www.curseforge.com/minecraft/mc-mods/configured)
- [InventorySorter](https://www.curseforge.com/minecraft/mc-mods/inventory-sorter)
- [Inventory Essentials](https://www.curseforge.com/minecraft/mc-mods/inventory-essentials)
- [TrashSlot](https://www.curseforge.com/minecraft/mc-mods/trashslot)

### Performance
- [Canary](https://www.curseforge.com/minecraft/mc-mods/canary)
- [Embeddium](https://www.curseforge.com/minecraft/mc-mods/embeddium)
- [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore)
- [ImmediatelyFast](https://www.curseforge.com/minecraft/mc-mods/immediatelyfast)
- [ModernFix](https://www.curseforge.com/minecraft/mc-mods/modernfix)
- [Saturn](https://www.curseforge.com/minecraft/mc-mods/saturn)
- [Starlight (Forge)](https://www.curseforge.com/minecraft/mc-mods/starlight-forge)

### Library / Framework / Dependency / Integration
- [Fusion (Connected Textures)](https://www.curseforge.com/minecraft/mc-mods/fusion-connected-textures)
- [SuperMartijn642's Core Lib](https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-core-lib)
- [SuperMartijn642's Config Lib](https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-config-lib)
- [JEI Integration](https://www.curseforge.com/minecraft/mc-mods/jei-integration)
- [JER Integration](https://www.curseforge.com/minecraft/mc-mods/jer-integration)
- [Balm (Forge Edition)](https://www.curseforge.com/minecraft/mc-mods/balm)