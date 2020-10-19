+++
title = "Vane"
date = 2019-07-31
[extra]
image = "/img/Vane.png"
[taxonomies]
types = ["game"]
+++

Make all the vanes toward one direction.
<!-- more -->
#### Metadata:
- Date: August 2019
- Entry to: NGC Game Jam
- Genre: Puzzle
- Engine: Unity 2019.1
- My Role: Lead Game Designer, Programmer
- Play at: [itch.io](https://mcatin.itch.io/vane)
- Source Code: [GitHub](https://github.com/igaryhe/Vane)

# Overview
Vane is a puzzle game with quite simple mechanism yet provide some really complex levels.

{{ youtube(id="dTA7I8cG_L0" class="youtube") }}

# Gameplay

## Goal
The goal of each level is to use the wind to make each of the vane towards the same direction. You are able to place a device named "Jalousie box" on an empty tile which could change the direction of the wind.

P.S. In case some of you might feel confused, the vane will point towards the coming direction of the wind.

## Control
This game is recommended to play on PC, as Unity WebGL is not well supported on mobile devices.

- Place "Jalousie box": Mouse click on empty tile
- Rotate "Jalousie box": Mouse click on the placed "Jalousie", and it will rotate for 45 degree.
- Camera rotation: Q/E
- Camera zoom in/out: Scroll wheel
- nCamera movement: Hold scroll wheel and move mouse
- Undo: Z (Notice undo will reset all the vanes' direction)
- Reset: R
- Return to level selection/title: Esc

# Design

## Idea
The theme of the game jam was a Chinese phrase: "万里同风". In Chinese, it means that "no matter where shares the same wind". We started the idea generation ever since we got the theme.

Me and another programmer are huge fans of puzzle games. Both of us have played a lot of puzzle games, and we share a similar taste of puzzle game design. With this as a prerequisite, we decided to make a **pure** puzzle game.

After the brainstorming and evaluating of each idea, we finally decided the rudiment of our core mechanism. There will be several vanes in each scene, and several streams of the wind blow through. Players should use items to change the path of the wind, in order to make all the vanes toward the same direction.

We chose this idea at last because my intuition told me that this set of rules is dynamic. We could make levels with depth by using this mechansim.

## Prototyping
We jumped straight into prototyping after we decided the core mechanism.
