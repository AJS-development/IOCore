# IOCore
A super efficient IO game engine written in JavaScript. It is the most efficient and secure IO game engine for NodeJS today.

## Features

* Multi-threading/servers - Multiple servers can be opened within one machine, each running on a different thread
* Secure Protocols - Secure binary protocols are randomly generated on server startup. Prevents hackers from interfacing with your game.
* Interpolation - Utilizes two optimized and scalable interpolation systems to make sure that all movement is smooth
* Optimised collision detection - Uses HashBounds to collide objects.
* Lag prevention

## Performance

IOCore is heavily optimised. Heres an example with Cytosis.IO

#### With one player + 2900 objects

<img width="1376" alt="screen shot 2018-12-13 at 5 34 37 pm" src="https://user-images.githubusercontent.com/13282284/49971722-6cc79400-fefd-11e8-99ba-3a4e1b1ec35b.png">

#### With one player + 2900 objects + 1000 bots

<img width="1376" alt="screen shot 2018-12-13 at 5 45 00 pm" src="https://user-images.githubusercontent.com/13282284/49972205-e0b66c00-fefe-11e8-8cf4-da65a5d31e4c.png">

