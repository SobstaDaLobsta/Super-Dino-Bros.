# CMP105 Alternative Project

_NOTE: This is an example based on the alternative project as if submitted for the Trunk assignment_

## Game 

**Dino Hanyman: Spanner in the Works** 

A two-level platformer prototype developed as an alternative trunk project to extend for CMP105 students from 2026 onwards. This project has most of the base requirements for a group submission. In the first level, the player has to navigate to the far right-side of the screen, avoiding pitfalls, and activate a lever before returning to the start. In the second level the player must investigate the high wall, backtrack to a box and jump into it from below to reveal a coin, colliding with the coin grants the ability to double-jump, using which they can navigate to the end of the level.

The engineering for this game is restricted to solely using the framework with few additions. 

**Controls:** 

WASD to move,
Spacebar to jump,
W to interact (works on pipes or doors),
R to reset (if you get stuck or fall down)
P to pause,
left mouseclick in the menu.

***Extension suggestions***

In addition to the proposal laid out below, there are several features which could usefully be added to this game as part of a branch project, here are a few:

* The game cannot be paused
* Entirely rework the player controller for precise teleportation-based movement rather than acceleration (which is odd in a platformer)
* Write a textureLoader or textureManager class
* Write a levelLoader that reads the tilemaps in from a file rather than them being hardcoded
* Create a level editor where players can use the full tileset to create their own levels
* Add more player actions -- the main character has a kick as part of their spritesheet
* Add enemies with platform-restricted pathing 
* Gravity manipulation 
* Create a platforming setpiece to act as the final mechanical challenge

## Student Details

**Student Name:** William Kavanagh

**Student Number:** 0000001

**Course:** _CGAD_ / _CGT_ I am of both courses, and of none.

---
---

# Proposal

## Brief Overview of game 

Super Dino Bros. (Brothers) is going to star a small, innocuous dinosaur that bravely took on the mantle of "hero of the princess" after she was whisked away by none-other-than Pteradon Bull, leader of the sky armies. To return her highness to safety our little dino must use any and all power-up found in the levels to push through Bull's armies in this side scroller, platformer stage-based world, capturing all forts at the end to progress. There will be multiple levels and at least two biomes with some sort of new feature to accompany them. Due to this being a parody of Mario Bros: any and all powerups will be in level and those levels will have multiple paths to take based on how skilled or unskilled the player is, with high risk attributed to higher reward. There will be no complex movement options like dashing or double jumping, but the simple ones like crouching, running and jumping will need to be used masterfully to complete harder levels. Talking about levels, I am planning, at least, five with at least three unique enemy types in each with the rest being variants of them. The game will also sport a lot of environmental hazards too. Time will also be elapsed during playtime, per level and lives will be the driving force of the player that will either be replenished by good gameplay, avoided completely or lost which will force the player to restart- five lives will be the default for any run.

## Must Have Features

* Power-ups: Magical items that, when picked up, grant the player either fire, ice or invincibility.

* Enemies: Bull's dinos, ground or flying but all just as dangerous as the last in bad circumstances.

* Level Engineering: Making a balanced experience with ingenious design that feels good to play through and has its shares of difficulty.

## Should Have Features

* Data-driven Level Loading: To create a level large enough to introduce the new mechanics without making the code a mess. 

* Lives and Losing: The play will only have a total of five lives. If they fall off a platform or hit any of the enemy dinos or hazards they will lose one life and if they get to zero lives they will see a game over screen.

* Pausing: The game will be able to be paused with a simple transparent overlay. (It might gets its own music)

## Could Have Features

Traversal: the use of pipes and doorways to loead other level chunks or sub levels to be found.

* A Heads-up Display: That shows the elapsed time, lives counter and indications of what item you may have.

* Enemy Animations: giving the dino armies their own aniamtions loops and different states of them.

## Wish to Have Features

* Checkpoints: There will be positions in the level where the player can restart from if they lose a life, should they have got far enough. These will be placed where the player gets new abilities.

* Coyote Time: The platforming will be enhanced by coyote time, a grace period during which the player can still jump even if they are not on a platform.

* Final Boss: The fight with Bull himself that will need to be unique and entertaining.

* Menus: The addition of a level select screen and just a simple roadmap to access. Settings that personalise the experience and a main menu with a catchy tune to boot.
