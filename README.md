# Car Game

## Project Overview
"Car Game" is a simple yet engaging arcade game developed using Pygame. The objective of the game is to control a car and avoid collisions with other vehicles while moving through lanes on a road. The game speeds up as the player progresses, increasing the challenge and excitement.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Game Mechanics](#game-mechanics)
- [Contributing](#contributing)
  
## Features
- **Interactive Gameplay:**
  - Control the car using the left and right arrow keys.
  - Avoid collisions with other vehicles to keep playing and increase your score.
- **Dynamic Environment:**
  - Randomly appearing vehicles in different lanes.
  - Speed increases as the player progresses.
- **Visual and Audio Effects:**
  - Realistic car images and crash animations.
  - Score display to keep track of the player's progress.
- **Game Over Screen:**
  - Displays a crash image and prompts the player to restart or exit the game.

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/car-game.git
    cd car-game
    ```

2. **Install required packages:**
    - Make sure you have Python and Pygame installed. If not, you can install Pygame using:
    ```sh
    pip install pygame
    ```

3. **Set up the game assets:**
    - Ensure the `images` directory contains the following images:
        - `car.png` (Player's car)
        - `pickup_truck.png`
        - `semi_trailer.png`
        - `taxi.png`
        - `van.png`
        - `crash.png` (Crash image)

## Usage
1. **Run the game:**
    - Execute the game script:
    ```sh
    python car_game.py
    ```

2. **Gameplay Instructions:**
    - Use the left and right arrow keys to move the car between lanes.
    - Avoid collisions with other vehicles.
    - The game ends if a collision occurs.
    - Press 'Y' to restart the game or 'N' to exit when the game is over.

## Game Mechanics
- **Lane Movement:**
  - The player can switch between three lanes: left, center, and right.
- **Vehicle Appearance:**
  - Random vehicles appear in different lanes and move down the screen.
- **Score and Speed:**
  - The score increases as the player successfully avoids vehicles.
  - The game speed increases after every 5 vehicles passed, making it more challenging.
- **Collision Detection:**
  - The game detects side swipes and head-on collisions, ending the game if they occur.

## Contributing
We welcome contributions to enhance the Car Game project! If you have suggestions or improvements, please fork the repository and submit a pull request.


---

Enjoy playing the Car Game and feel free to customize it to add more features and improve the gameplay experience!
