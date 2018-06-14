Project Title Classic Arcade Game

Table of Contents:
1. Game description
2. How to play
3. Programming description
4. How to run

Game description
There are two main characters in this game: the player and the enemy. In order to win the game, the player has to reach the water without colliding into one of the enemies.

How to play
1. Player uses arrow keys to move up, down, left and right
2. Player needs to avoid collision with enemies  
3. Enemies move in random speed... so watch out!!
4. If player collides with one of the enemies, the game will reset
5. If player reaches the water, the player wins.

Programming Description
The game is written in JavaScript. I used starter code provided by Udacity. Then, I used object-oriented programming to add basic functionality.
1. I created allEnemies and player objects.
2. I used Enemy.prototype.update(dt) method to create enemies' movement, random speed and check collision.
3. If player-enemy collides, the player will be return to its initial position (game resets).
4. I created alert, if player reaches water (wins). Then, the game will reset.

How to run
https://github.com/ellyanalinden/MainArcadeGame.github.io.git

References:
1. Object-oriented JavaScript for beginners https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS
2. Object-oriented JavaScript Notes (Udacity course) https://docs.google.com/document/d/1F9DY2TtWbI29KSEIot1WXRqqao7OCd7OOC2W3oubSmc/pub?embedded=true
3. Win the game https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_breakout_game_Phaser/Win_the_game
4. How to host a website https://www.youtube.com/watch?v=3jt-J4Rc__M
5. https://github.com/brenopolanski/udacity-classic-arcade-game-clone
6. https://github.com/caraya/udacity-game
7. https://github.com/FoteiniK/Project-Arcade-game
