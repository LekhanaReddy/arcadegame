# Classic Arcade Game Clone Project

## Table of Contents

-   [Instructions](#instructions)
-   [Information](<#project details>)
-   [What I have done](#I done)
-   [Game Playing](<#how to play>)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking.

## INFORMATION

-   Clone the repository from the udacity that contains the details and files
    1.  style.css
    2.  index.html
    3.  js (app, engine, resorces)
    4.  images

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

## What I have done

1.  To run the application load the `index.html` file in your favourite
    browser. I didn't found any canvas on the screen and check the developer console found few errors and resolve those errors
    -   Created an object for all enemy object in the form of array as `allEnemies`
    -   Created an object for the player
    -   Create constructor for player
2.  Initially set positions of player and enemies
3.  for every movement of player set coordinates for appropriate key.
4.  Speed of enemies are taken randomly in which the game runs at the same speed for all computers.

## Game Playing

1.  Player moves corresponding direction by pressing a key(left, right, up, down) until it does not move away from specified width and height.
2.  If player move to water level then player is reset to initial position.
3.  If player and enemies collide with each other then player reset to its initial position.
