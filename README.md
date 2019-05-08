# Classic Arcade Game Clone Project

## Table of Contents

- [Instructions](#instructions)
- [Information](#project details)
- [Game Running](#running)
- [Game Playing](#how to play)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking.

##INFORMATION
* Clone the repository from the udacity that contains the details and files
   1. style.css
   2. index.html
   3. js (app, engine, resorces)
   4. images

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

## Game Running
1. Created a constructor for Enemy class and player class.
2. Created an object for all enemy objects in the form of array as allEnemies.
3. Created an object for the player object in a variable called player.
4. initially set positions of player and enemies.
5. for every movement of player set coordinates for appropriate key.
6. Speed of enemies are taken randomly in which the game runs at the same speed for all computers.
7. Speed of enemies are taken randomly in which the game runs at the same speed for all computers.

## Game Playing
1. player moves corresponding direction by pressing a key(left, right, up, down) until it does not move away from specified width and height.
2. If player move to water level then player is reset to initial position.
3. If player and enemies collide with each other then player reset to its initial position.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).
