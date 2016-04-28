# TorusCraft
## Based entirely on PythonCraft
A program to procedurally generate 3-dimensional worlds made of cubes and view the evolution of the landscape over time. Right now it generates the world on the fly and launches the pyglet window as soon as it's been generated, so just run main.py with Python. 

The current version uses textures from Mojang's Minecraft, and certain elements of the program structure were inspired by Michael Fogleman's "Minecraft" repository.

## The twist
![screenshot of the torus world](docs/torus_craft.png)

#### Dependencies:
* Pyglet
* Numpy
* PyPlatec

`pip install pyglet numpy pyplatec`

#### Controls:
__WASD:__ Normal movement
__Space:__ Fly up
__Shift:__ Fly down
__Esc:__ Pause
