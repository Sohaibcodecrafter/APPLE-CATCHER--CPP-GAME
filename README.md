# APPLE-CATCHER--CPP-GAME
A NEW GAME BASED ON RAYLIB AND CPP.(MY FIRST EVER GAME MADE)
🍎 Apple Catcher Game 🎮
Welcome to Apple Catcher, a fun and addictive game where quick reflexes and strategic movements are key to scoring high and surviving the falling frenzy! 🌟 Test your skills, catch delicious apples, avoid dangerous bombs, and achieve the ultimate high score!

🕹️ Game Features
Dynamic Gameplay: Apples fall faster as you progress—can you keep up?
Challenging Obstacles: Dodge bombs to avoid losing lives and ending your game!
Interactive Menu: Easy-to-navigate menu with options to start, view high scores, or quit.
High Score Tracking: Your personal best is remembered for ultimate bragging rights!
Immersive Experience: Relax with cheerful background music or feel the tension of the game-over sound effect.
Simple Controls: Arrow keys to move the bucket left and right.
🌟 How to Play
Catch Apples: Move the bucket to catch as many falling apples as possible to increase your score. 🍎
Avoid Bombs: Stay alert! Colliding with a bomb will cost you a life. 💣
Survive: You have 5 lives. Lose them all, and it's game over!
Pro Tip: Keep an eye on the increasing speed of apples—it's a game of endurance and focus!

🛠️ Game Architecture
The game is built in C++ using the Raylib library for graphics and input handling. Here's a sneak peek into its architecture:

Classes:

GameObject: The base class for all game entities (bucket, apples, and bombs).
Bucket: Represents the player’s bucket. Moves left and right to catch apples.
Apple: Falling objects that players aim to catch.
Bomb: Hazardous objects to avoid.
CollisionFunction: Handles all collision logic and game state updates.
Game States:

MENU: The main menu screen.
GAME: The core gameplay loop.
OPTIONS: Displays the high score.
GAMEOVER: The game over screen.
🚀 Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/apple-catcher-game.git
cd apple-catcher-game
Install Dependencies:
Download and set up the Raylib library for your system.

Run the Game:
Compile and execute the program:

bash
Copy code
g++ -o AppleCatcher main.cpp -lraylib
./AppleCatcher
🎨 Media Assets
Textures:

bucket.png: The trusty bucket for catching apples.
apple.png: The delicious fruit you aim to catch.
bomb.png: The dangerous hazard to avoid.
tree.png: A beautiful background for a calming gameplay experience.
menu.png: An interactive menu screen.
gameover.png: The screen that challenges you to try again!
Audio:

sound.mp3: Background music to keep you immersed.
gameover.mp3: A sound effect that sets the tone for defeat (but not forever!).
💡 Why Play This Game?
This game is a perfect blend of fun and challenge! Whether you're a casual player or a hardcore gamer, Apple Catcher offers something for everyone. Compete with yourself, chase your high score, and enjoy the satisfaction of mastering this dynamic arcade game.

❤️ Contributing
We welcome contributions to make Apple Catcher even better! Feel free to submit issues or pull requests. Let's work together to make this game the best it can be.


