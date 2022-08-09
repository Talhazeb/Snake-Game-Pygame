# Snake-Game-Pygame


Open terminal in the respective folder of game.
Execute command:
    pip install pygame

Execute Game:
    python snake.py

For additional settings change do the following:

How to change game settings
In the folder, there is a file called `settings.json`. Inside of this file, there are settings that can be changed.
- "scale" : 15 - This changes the scale of the whole game (the size of the grids).
- "initial_snake_size" : 5 - This changes the initial snake size. How many squares you want the snake to begin with
- "fruit_color" : [0, 255, 255] - Set the color of the fruit. By default it is cyan, but you can change to any color in RGB
- "snake_color" : [255, 255, 255] - Changes the snake color
- "frame_rate" : 15 - This changes the framerate of the game. the higher, the faster.
- "screen_size" : 500 - This setting changes the width of the screen. Don't worry about the height because the game has an aspect ratio.
- "collide_on_walls" : false" - Change if the player will lose if it collides with the walls or not.

## Controls
| ↑ | up |
| ↓ | down |
| ← | left |
| → | right |
| R | restart when dead |

Modules required:  
 - Pygame : `pip install pygame`
