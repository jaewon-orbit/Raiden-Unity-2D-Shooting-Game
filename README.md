# Raiden — Unity 2D Shooting Game

A Raiden-inspired Unity project I built while learning how to structure a 2D game.

## Goal and Implementation

The game combines player movement, enemies, projectiles, scoring, and transitions between ready, playing, and game-over states.

- Reused bullets through object pooling.
- Handled objects leaving the play area with a destruction zone.
- Managed the game flow and retry interface through game states.
- Saved the high score between sessions.
- Used a scrolling background to suggest forward movement.

Working on these parts together helped me understand how gameplay, object lifecycles, and UI fit into a small game.

## Demo

[![Raiden gameplay](https://img.youtube.com/vi/aI9E4yKLZ2Y/0.jpg)](https://youtu.be/aI9E4yKLZ2Y)

## Running the Project

Clone this repository and open it in Unity. Check `ProjectSettings/ProjectVersion.txt` for the project's editor version. Use Unity's Build Settings to choose a target platform and build the game.

The documented controls are W/A/S/D for movement and left click to fire.

## Scope

This is a learning project. The demo shows gameplay; no performance benchmark is reported.

**Tools:** Unity, C#
