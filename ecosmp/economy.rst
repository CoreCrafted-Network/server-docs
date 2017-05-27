===============
Economy System
===============

Unlike other survival server, we have the official shops(that means the shop you
can sell/buy things with server) disabled. Which means you only
got one way left to earn your living : Trading [#]_

Trading can involve any kind of exchange, reguardles  it is with money or plain items. The following will
list and explain different ways of trading, in detail

.. [#] As of 1.3 Update, an alternative way of earning money
       is planned to be implented

------

Direct Trading
===============

You can trade with other players directly within a range
through the **Trading GUI**. In this server, TradeMe (a world famous
trading plugin) is used.

.. note:: Substitute [player] with the target playername

The following will describe the steps for doing a trade with
TradeMe.

- Before starting the trade, remember to inform the player you want to trade
  with
- Execute the command ``/trade [player]``
- Wait for the other side to reply
    - To accept , run ``/trade accept``
    - To deny , run ``/trade deny`` or click the ``[x]``
- A trading GUi will appear after the trade is initiated
- The left side is what you offer others, while the right side is what you will receive
- You can adjust the amount of money/exp/McMMO exp/Residence that will be offered
- Click the red bar at the left side to agree trade (The red bar will turn green after clicking)
- When both agree, the trade will countdown and be completed.

Shops
=====

There's several method to sell out(trade) your items passively

Shopkeepers (Villager trade)
----------------------------
This type of shop require you to have a spawnegg of the type of NPC shop you want to create, and then bound it to a chest
where each column represent a trade (first 2 row is the required item, last row is trade result). This is the simplist way to
trade items without involving money

Here is an example:

+------------+------------+
| apple      |  carrot    |
+------------+------------+
| 4 iron     | 5 emerald  |
+------------+------------+
| gold apple | potato     |
+------------+------------+

If you put your items like this, your 2 trade will be like this:

- Trade an apple with 4 iron ingot for a golden apple
- Trade a carrot and 5 emerald for a potato

Chest Shop
----------

Suppose every economy survival server have this feature installed. In this server, we are using quick market instead of
the original chestshop plugin (due to the plugin has stopped developing).

As it is a relatively less popular plugin, so here's a little tutorial on creating your chest stop.

- To make your own shop, place a sign on your chest with [Shop] on first line
- Fill out the rest of the sign with the following information including the first line (layout of the sign): ::

    [Shop]
    <amount>
    <price>
    <buy/sell>

- Click the sign with the item you want to sell/buy
- Profit!

To configure your shop, right click the sign and a configuration GUI will come out.

iBay 2
======

The "iBay 2" is a special ingame shop platform what allows players to psot their item on it for selling and carrying out auctions. It is an updated version of the iBay , which have less features. The base command for accessing the iBay is simply ``/ibay`` or ``/ca`` or ``/ah``

- To put your item on the platform for sell, use ``/ibay sell [price]`` while holding your item prepare to sell
- To put your items for players to auction, use ``/ibay bid [price]`` while holding your item to bid (same as selling)
- To buy items / auction items, open the platform site with ``/ibay``, click on the item and then confirm the transaction

.. note:: Replace [price] with any number you want to be the price.

The Bank
========

It is something that appeared before, but closed down unfortunately due to depletion of capital. Hope there's another bank
in the future time
