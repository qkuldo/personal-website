---
layout: post
title: Spritestacking
---

## Welcome
In my game Bumpgun, there is a 3d effect used for the 2d sprites in the game.

https://github.com/user-attachments/assets/fc60f47a-11fd-4582-a2d5-7f3eb3f10f51

If you're wondering, this is how the file for the player looks like:

![Player image](content/player_skin1.png)

It resembles a spritesheet, but instead of separate animations for the entire player, there are separate parts of the player body.
There are some similar frames, but those are just for animating the player's limbs when jumping, and for the player's gun mode.
The 3D effect is caused through **spritestacking**, a method to render certain layers of the .