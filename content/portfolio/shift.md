+++
title = "SHIFT"
date = 2019-09-11
[extra]
image = "/img/SHIFT.png"
[taxonomies]
types = ["game"]
+++

When you can shift between wall and floor.
<!-- more -->
# Metadata:
- Date: September 2019
- Entry to: BOOOM Game Jam
- Genre: Puzzle Game
- Engine: PICO-8
- My Role: Game Designer, Programmer
- Play at: [itch.io](https://igaryhe.itch.io/shift)

# Overview
SHIFT is a puzzle game which inspired by classic puzzle game Sokoban and Antony Lavelle's Flash game SHIFT.
{{ youtube(id="0pqtEpHvxdU" class="youtube") }}

# Gameplay

## Goal
Each level consists of two colors. The player controls the movement of the character. If the character is white, it could move on blue tiles, and it will collide on white tiles; if the character is blue, it could move on the white tiles and it will collide on blue tiles. The goal of each level is to reach the portal.

## Control
Players could use "SHIFT" ability to walk across different colors. The picture below shows how it works.

{{ figure(src="/img/shift-control-1.png" caption="Here the character collide with the wall") }}

Here, the chacacter collides with the "wall".
{{ figure(src="/img/shift-control-2.png") }}
The red indicator on the left up corner shows that we've enabled the SHIFT ability.
{{ figure(src="/img/shift-control-3.png") }}
Then we could move into the blue tiles, and shift the color of our character.

What's more, as we've mentioned, the game is a combination of SHIFT and Sokoban. 
{{ figure(src="/img/shift-control-4.png") }}
If there is a single block of the "wall" on your moving direction.
{{ figure(src="/img/shift-control-5.png") }}
You could easily push it.
