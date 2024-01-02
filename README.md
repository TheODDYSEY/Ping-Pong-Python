# Pong Game with Python and Pygame

This repository contains the source code for building a simple Pong game using Python and the Pygame library. The game involves two paddles and a ball, with players attempting to score points by bouncing the ball past their opponent's paddle.

## Table of Contents

1. [Game Setup](#game-setup)
2. [Creating the Ball](#creating-the-ball)
3. [Creating the Player Class](#creating-the-player-class)
4. [Creating the Game Table](#creating-the-game-table)
5. [How to Play](#how-to-play)
6. [Project Structure](#project-structure)
7. [Requirements](#requirements)
8. [Controls](#controls)
9. [Contributions](#contributions)
10. [License](#license)

## Game Setup

Ensure that Pygame is installed on your computer. You can install it using the following command:

```bash
$ pip install pygame
```

Create a directory for the game and include the following files: `settings.py`, `main.py`, `table.py`, `player.py`, and `ball.py`.

Here's the initial content for `settings.py`:

```python
# settings.py
WIDTH, HEIGHT = 990, 450
player_width, player_height = 20, 90
```

## Creating the Ball

Create a `Ball` class in `ball.py`:

```python
# ball.py
# (code for the Ball class)
```

Refer to the source code for the complete implementation of the `Ball` class.

## Creating the Player Class

Create a `Player` class in `player.py`:

```python
# player.py
# (code for the Player class)
```

Refer to the source code for the complete implementation of the `Player` class.

## Creating the Game Table

Create a `Table` class in `table.py`:

```python
# table.py
# (code for the Table class)
```

Refer to the source code for the complete implementation of the `Table` class.

## How to Play

1. Clone the repository.
2. Ensure you have Python and Pygame installed on your system.
3. Run the game using `python main.py`.
4. Use the keyboard to control the player paddle.
5. Enjoy the game and try to score against the AI opponent!

 

## Project Structure

- **main.py:** Main script to run the Ping Pong game.
- **settings.py:** Contains constants for the game window width and height.
- **table.py:** Class implementation for the Pong game table.
- **player.py:** Class implementation for the player paddle.
- **ball.py:** Class implementation for the ball.

## Requirements

- Python
- Pygame library

## Controls

- **Up Arrow:** Move the player paddle up.
- **Down Arrow:** Move the player paddle down.
- **Close Window Button:** Quit the game.

## Contributions

Contributions, bug reports, and feature requests are welcome. Feel free to open issues or submit pull requests to enhance the game.

## License

This project is licensed under the [MIT License](LICENSE), allowing flexibility for usage and modification.
