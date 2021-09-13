# brickrigs-mod-examples

Contains four examples, only compatible with Unreal Engine 4.22 and the last version of Brick Rigs that used that engine.

Feel free to update or improve them!

All of the examples (except for MapLoader itself of course) are designed to work with MapLoader.

## BRPlanet
Unfinished demo on how to apply radial gravity to bricks. Doesn't work very well due to the game reporting incorrect mass on bricks.
The map also has a debug widget that prints the name and mass of all primary components (i.e. bricks).
This widget kills the ingame performance, so you would have to remove it if you want to use GravitySource yourself.

## BRWaterTest
Demo on how to simulate water with bouyancy. If you want to use it yourself you can copy the `BrickWaterPhysics.uasset` to your own project and put it in your level.

## BRTest
This is the first custom map ever, here mostly for historic purposes.

## MapLoader
This is source of the MapLoader 3. May also contain other stuff I can't remember.

