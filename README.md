# Project KAGE
One week, make it count.
## Premise
影 (かげ)
1) shadow; silhouette; figure; shape
2) light (stars, moon)

The core concept of the two enemies; light and darkness.
## Plan
### Matthew
- Enemy Setup
- Enemy AI
- Bug Fixing
### Gareth
- Level Design
- Texturing
- Character Setup
### Mac
- Level Modelling
- Player Modelling
- Audio
## Log
### 0 - Project Started (5/7/17 by Matthew)
No description.
### 1 - Enemies Created (6/7/17 by Matthew)
Light enemy started and mostly completed. Shadow enemy started and basic movement done; rotation yet to be figured out.
### 2 - Enemy Movement Improved (7/7/17 by Matthew)
Light and Shadow enemy movements have been updated, they now rotate and walk between predefined points. Shadow has been set to run these points while Light has been set to walk them.
### 3 - Helped Gareth Fix Collision Boxes (9/7/17)
Gareth and Mac were having a weird problem with collision over various parts of the level. The player was getting stuck and we weren't sure what the problem was. Eventually Gareth and I figured out one of the kitchen's objects had a messed up collision box so we deleted it and that seems to have fixed the problem.
### 4 - Helped Gareth Create 3D UI (9/7/17)
We wanted a UI to pop up prompting the player to press a key when they were within range of a door.  I contributed to most of the blueprint.
### 5 - Changed Shadow Enemy Collision (9/7/17)
The Shadow enemy collided with the player despite the mesh not being rendered, I changed it so that it could still interact with the environment (to scare the player) without colliding with the player.