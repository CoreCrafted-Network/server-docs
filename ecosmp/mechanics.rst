===============
Game Mechanics
===============

A free zone server is not meaning that open a plain survival server and let you waste your time inside. Instead, we implement
a lot of exclusive features so that players could discover them by themselves. Some features are rather tricky or not easy
to be noticed, therefore, this section is designed to help exploration.

----

Storage Safety
================

Our server have **LWC** installed to protect your inventory blocks (e.g. furnace, chests, dispensers), doors or even a single block.  By default, storage blocks (include furnaces) are locked
by you when you place it down, and you are the only one who can access the chest.

To change the security level of the block, you will need to excute a command
and tap on the block you want to modify.

Here is some usefule commands that you may want to use:

- Changing storage blocks/doors access permission: ``/cmodify [playername] [anotherplayer] [evenmoreplayer]`` (This command will gain access to all players mentioned in the command)
- Unlock your storage blocks/doors: ```/cremove`` or ``/unlock``
- Lock back your storage blocks/doors: ```/cprivate`` or ```/lock``

.. caution:: Both ``/cremove`` and ``/unlock`` will purge **ALL** protection. It's adviced to use ``/cmodify`` to edit permission instead
.. note:: Quite a lot of player has returned that storage blocks can't be used with hoppers. In this case, try running ``/lwc flag hopper on`` and punch the storage block.

-----

Slimefun
=========

**Slimefun** is a really special plugin introduced to the server at the 1.0 Official Release (also known as the initial
release). This plugin features a wide spectrum of extension items that comes from mods. The item genre is ranging from
machines, to magic stuff, allow you to have a taste of playing mod pack server without needing to install a single mod to
your minecraft client.

.. image:: https://corecrafted.net/resource/2016-12-04_15.09.30.jpg

In case you lost your Slimefun Guide Book , you can always get one back for free with ``/guide``

Slimefun comes with different addons, different addons will do different things:

- SlimeExpansion
    - Slime Expansion is an end-game extension that allows you to break bedrock, make UU matter.... (IC2 emulation)
      Exotic Garden

- Exotic Garden
    - Comes with juice that made with juicers from the slimefun core module, and a lot of food that you can find in the real life
    - It also adds magical plants , that allows you to plant invaluable minerals.
      There are different fruit trees and bushes as well ... apples now come with 2 look (2d and 3d)

- Lucky Block
    - This one is relatively not important, as it adds the few lucky block items to the game, and they will give you surprice when you break them :)\

The first join tutorial space has covered and demonstrated the usage of slimefun and other plugins. But if you skipped it
for the sake of speed and missed this awesome tutorial, you can always get there by ``/warp new ``

.. image:: https://corecrafted.net/resource/2016-12-04_15.09.48.jpg

Additionally, there's a video tutorial on how to obtain dusts in slimefun

.. raw:: html

    <iframe width="90%" height="320" src="https://www.youtube.com/embed/yvhhL9VZOlg" frameborder="0" allowfullscreen></iframe>

-----

Enchanting
==========

You all know that putting item on enchanting table can guarentee an enchantment on the item, but have you ever thought
of trying another method of enchanting?

In this server, you can redeem special yet powerful enchantment books with the cost of xp levels. Here is a simple
procedure on applying custom enchantments on your beloved tool:

- Run ``/enchant`` or ``/ce`` to open the Crazy Enchantment Interface
- Buy different tier of enchantment books based on your need (higher tier it is , the more powerful book you get)
- Apply the enchantment to your item by dragging the book over your item in your inventory.
- Some book will have a ridiculously high break/fail chance, so the following may help:

    - **White Scroll** will prevent your item from being broken by the enchantment book
    - Applying **Magical Angel Dust** to enchantment book will increase success chance
    - Applying **Magical Fixing Dust** to enchantment book will decrease breaking chance

- If you want to retrieve custom enchantments from the item, you may consider using **Black Scroll**

-----

Thirst
=======

The **Thirst** system is a special feature added to this server to increase the feel of realistic (More likely annoy you in a more
natural way). This added hydration level to the player, which you have to maintain your hydration level at a reasonable range.

.. image:: https://corecrafted.net/resource/2016-12-11_16.54.25.jpg

The hydration level is presented at the top of your screen with a caption of "Hydration level".
The hydration level will go down from time to time, and the rate of depletion is determined by the biome you are in.

Biome depletion rate:
    - normal: 1
    - savannah: 2
    - desert: 4
    - jungle: 2
    - nether: 4

If you don't drink water regularly and let your hydration continue to drop, debuff effect will be applied on you.

Warning Level:
    - thirsty: 40%
    - parched: 20%
    - dehydrated: 10%

**Differeny Type of Water**

- Pure Water , restore 30% of hydration
.. image:: https://proxy.spigotmc.org/2fb56761f8d35f58f9b08902f028da660fe2a950?url=http%3A%2F%2Fwww.byte.org.uk%2Fmc%2Fwp-content%2Fuploads%2F2015%2F01%2Fthirst-craftsnow.jpg

- Boiled Water , restore 25% of hydration
.. image:: https://proxy.spigotmc.org/511b1951f2334b38ddd740260c1477601559d5b0?url=http%3A%2F%2Fwww.byte.org.uk%2Fmc%2Fwp-content%2Fuploads%2F2015%2F01%2Fthirst-craft-300x99.jpg

- Normal Water (Water collected from water block) , restore 20% of hydration

-----

Other Mechanics
================

McMMO
------

The McMMO is installed purely for enhance basic survival experience. It makes your life easier at some point because it is doing relatively minor changes to the server (Unlike slimefun, this changes the game completely)

For more details on this plugin, you may refer to its official wiki `HERE`_

.. _HERE: http://mcmmo.wikia.com/wiki/McMMO_Wiki

Transfer Pipes
---------------

Transfer pipe is a less expensive solution on handle item transfering without needing to use tones of expensive hoppers or even more expensive slimefun cargo management system.

To create a working pipe, you may refer to the following picture:

.. image:: http://wiki.sk89q.com/w/content/b/ba/CraftBookPipes.png

*Small Picture from CraftBook Official Wiki*

- The pulse lever is used as a redstone sigal source for telling the stick piston to **Pull** things **from** the chest it is facing , into the destination inventory which the regular piston on the other side is facing
- Each time the sticky piston receive a single redstone signal, a **stack** of item will be pulled the destination

Bookshelves
-----------

Try right-clicking a bookshelf, you will get a single row (9 slot) of storage space that only accept enchantment books or normal books. It comes in
quite handy for storing enchantment books at the bookshelves around enchanting table, isn't it?
