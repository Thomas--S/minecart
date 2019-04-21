Minecart
========

**A minecart running through unloaded area.**


Browse on: ![GitHub](https://github.com/joe7575/minecart)

Download: ![GitHub](https://github.com/joe7575/minecart/archive/master.zip)

![minecart](https://github.com/joe7575/minecart/blob/master/screenshot.png)


Minecart is based on Cards, which is
based almost entirely on the mod boost_cart [1], which
itself is based on (and fully compatible with) the carts mod [2].

The model was originally designed by stujones11 [3] (CC-0).

Cart textures are based on original work from PixelBOX by Gambit (permissive
license).


1. https://github.com/SmallJoker/boost_cart/
2. https://github.com/PilzAdam/carts/
3. https://github.com/stujones11/railcart/


Original Features
-----------------
- A fast cart for your railway or roller coaster (up to 7 m/s!)
- Boost and brake rails
- Rail junction switching with the 'right-left' walking keys
- Handbrake with the 'back' key

New Features
------------
- Minecart has its own cart in addition to the standard cart.
- The minecart can "run" through unloaded areas. This is done by 
  means of stored routes as mod storage. If the area is unloaded
  the cart will simply follow the predefined route until the an
  area is loaded again. In this case the cart will be spawned and
  runs as usual.
- To store a route, a player has to place rail buffer on both ends,
  and use the minecart to ride the route in both directions.

Use Case
--------
The main use of the minecart is for item transport from mines,
ideally by means of an automation mod like Signs Bot.
https://github.com/joe7575/signs_bot

Introduction
------------

1. Place your rails and build a route with two ends (junctions are not allowed or ignored)
2. Place a Rail Buffer block at both ends
3. Drive the route in both directions (teach-in), starting at the Rail Buffers
4. Now you can drop items into the Minecart and punch der cart to get started

History
-------

2019-04-19  v0.01  first commit
2019-04-21  v0.02  functional, but no support for junctions
