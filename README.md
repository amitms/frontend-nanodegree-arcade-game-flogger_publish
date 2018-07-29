Frogger: frontend-nanodegree-arcade-game 
==================================================================================

## 1. Introduction:

Frogger is a classic arcade game. Objective of the game is to get player reach water accross by avoiding obstables (enemies). once player gets accross score of 10 received. highscore is recorded and can be cleared by reset. It is built with object-orientated Javascipt in order to fulfill part of Udacity's front end nano-degree program.

javascript app.js and index.html is modified and rest of css engine.js, resources.js are left intact as per requirement.

[![preview](./images/preview.JPG)](http://amitms.github.io/frontend-nanodegree-arcade-game-flogger/)


## 2. Installation and run:

* Offline installation: 
For offline gameplay, all files must be cloned or downloaded from https://github.com/amitms/frontend-nanodegree-arcade-game-flogger .

Open 'index.html' in your browser and start the game.

## 3. Instructions(how to play)
To play the game, simple move the player with arrow keys (up/down/left/right). click reset button to clear scores and player locatyon. 


## 4. Games features 
* checkCollisions:

collision detection is done if player is within 25px of an enemy (x or y axis) and reset the game if true

code:
 ```if (player.x < this.x + 25 &&
        player.x + 25 > this.x &&
        player.y < this.y + 25 &&
        25 + player.y > this.y) {
        player.x = 200;
        player.y = 380;
 ```
* alert:
background changes to red when collided.
