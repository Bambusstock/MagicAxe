DRAFT MagicAxe - Magic axes for Craftbukkit using the Bukkit API
=============================================================

I was building a castle and frustrated of breaking big trees into small blocks. Every time I had to jump to the treetop and cut all leaves away to
find that missing wood block. I was using MCmmo but the Treefaller was just happy medium. So I had a look on the plugin list and can't find something
practical. So I made this plugin.

Features
--------
- Cut down a tree with breaking his root.
- Use more than one axe type (wood, iron etc)
- Saplings will be dropped.
- Configurable (see Configuration section for more information)
- Permission

Some more information on the mechanics
--------------------------------------

By default the "MagicAxe" is the golden axe. Why? I thought: the user should be able to fell a huge tree by break his root block.
The other wood blocks should be broken by the plugin to make it more comfortable felling big trees. If I add a damage to each block who was broken
the gold tool will be lost. But if I add just damage for the broken root block you could use the tool more often, put not for small trees
because this would be waste.

(Later I added a option to enable damage per block, so if you like to use the plugin for speed up tree felling enable this.
 See configuration section for more information.)

Configuration
-------------

### `magicAxe` (Default: 286)

Define one or more magic axes triggering the magic felling effect.

#### `dropSapling` (Default: 5)

Define the amount of saplings to drop. Set to 0 if you don't wan't to drop saplings.


#### `cutLeaves` (Default: false)

Set to true if you wan't to cut away the leaves.

#### `damagePerBlock` (Default: 1)

Define the amount of minutes between one run of the scheduler and the next.

### `damagePerLeaves` (Default: true)

If set to true, there will be damage added to the axes for leaves.

Permissions
-----------

### MagicAxe.usage (Default: true)

Set who can use the magic axe.


Known Bugs
----------


Possible features:
------------------
- Command to toggle magic axe function
