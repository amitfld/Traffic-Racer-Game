# Traffic Racer Game in Jack Language
This project is an implementation of Traffic Racer game using the Jack programming language. The game is designed to run on the Nand2Tetris platform.

## Project Structure
The project consists of the following files:
- `Main.jack`: Acts as the game's entry point, managing its high-level execution.
- `TrafficRacesGame.jack`: Serves as the central game engine, managing the primary game loop. synchronizing gameplay
events, and handling visual updates.
- `GameSetup.jack`: Prepares and visually sets up the game environment before gameplay begins.
- `ScoreBoard.jack`: Tracks and dynamically displays the player's score throughout the game and updates the high score during gameplay, preserving player progress.
- `Falied.jack`: Manages the game-over state and provides functionality for restarting/quitting the game.
- `Random.jack`: Introduces randomness into gameplay mechanics by generating varied positions for obstacles
and collectibles.
- `Car.jack`: Handles player-controlled car functionality, specifically movement.
- `Dollar.jack`: Governs collectible dollar behavior and scoring logic.
- `Barrel.jack`: Implements the barrel obstacle in the game.
- `Cone.jack`: Implements the cone obstacle in the game.
- `Tree1.jack & Tree2.jack`: Implements the animated tree visuals.

## How to Run
1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/amitfld/Traffic-Racer-Game.git
    cd Traffic-Racer-Game
    ```
2. Load the jack files into the jack compiler:
    - Open the [jack compiler](https://nand2tetris.github.io/web-ide/compiler)
    - Load the folder containing all the `.jack` files of the project
    - Click 'Compile'
    - Once compiled, click 'Run'
3. Start the game:
    - Adjust 'Execution speed' to 'Fast'
    - Click '>>' (Run)
    - Click 'Enable Keyboard'
    - Start playing!

## Game Instructions
1. The game will only begin when you press the 'space' button.
2. Use right and left arrow buttons to move the car to avoid obstacles and collecting dollars
3. The game ends when you hit an obstacle (cone or barrel). a Game Over screen will appear.
4. Press 'R' to restart the game (maintaining high score and money collected). 
   Press 'Q' to quit the game.

## Game Demo
[![Traffic Racer Demo](thumbnail.png)](https://drive.google.com/file/d/1g42hettqR6rmlcHG4pEhDaiUul0Gw2mb/view?usp=drive_link)

**The full demo can be found [here](https://drive.google.com/file/d/1jfF3s7Ixz-eheqHtRInSOSUI5TwAaScC/view?usp=sharing)**

## Authors
- Amit Feldman
- Yotam Markman

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/amitfld/Traffic-Racer-Game/blob/main/LICENSE) file for full details.