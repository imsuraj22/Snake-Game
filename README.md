# Snake Game

![image](https://github.com/imsuraj22/Snake-Game/assets/100610668/72da0e3a-500c-4b26-a5bc-55700f049e4b)


## Description

The Snake Game is a classic arcade game in which the player controls a snake that moves around the game board, eating food items to grow in length. The goal of the game is to achieve the highest score possible by eating as much food as possible without the snake colliding with itself or the game boundaries.

This implementation of the Snake Game is written in Java and utilizes Swing components for the graphical user interface (GUI).

## Features

- Snake Movement: The snake can move in four directions - up, down, left, and right. It changes direction based on user input (arrow keys).
- Food Generation: Food items appear at random positions on the game board for the snake to eat.

## Installation

1. Clone or download this repository to your local machine.
2. Make sure you have Java Development Kit (JDK) installed on your system.
3. Open the project in your preferred Java IDE (e.g., Eclipse, IntelliJ).
4. Compile and run the `SnakeGame.java` file to start the game.



## Automatic Pathfinding

In this Snake Game, the snake automatically finds the path to reach the food item using the Manhattan Distance formula. The Manhattan Distance, also known as the Taxicab Distance, is the sum of the absolute differences in the coordinates of two points. By calculating this distance, the snake chooses the direction that minimizes the distance to the food item without any direct user input for pathfinding.

## Contributing

Contributions to this project are welcome. If you have any suggestions or want to report issues, feel free to create a pull request or open an issue in the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

