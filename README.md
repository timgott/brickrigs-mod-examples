# brickrigs-mod-examples

Contains two examples:

## BRPlanet
Unfinished demo on how to apply radial gravity to bricks. Doesn't work very well due to the game reporting incorrect mass on bricks.
The map also has a debug widget that prints the name and mass of all primary components (i.e. bricks).
This widget kills the ingame performance, so you would have to remove it if you want to use GravitySource yourself.

## BRWaterTest
Demo on how to simulate water physics. If you want to use it yourself you can copy the `BrickWaterPhysics.uasset` to your own project and put it in your level.
