# Lab 16
## Conway's Game of Life

### Conway's Game of Life

This is not really a game.  It is an implementation of a cellular automata that John H. Conway chose to call the “Game of Life.” The computer simulation is of the life and death events of a population of bacterial organisms.  This program will determine the life, death, and survival of bacteria from one generation to the next, assuming the starting grid of bacteria is considered generation zero.  Sometimes the outcome is that all organisms die.  Other times they end up in a static or oscillating world.  Other times, they form organisms that generate new life forms that glide across the screen. 

### Game Specifications

The sizeof the grid is set to a square 60 x 60.  Different sized grids produce different results.

### Model-View-Controller Framework

This application uses the Model-View-Controller(MVC) design framework. You don't have to worry too much about it, since the `LifeView.java` and `LifeController.java` classes are already written for you. If you want some more information on MVC, here are some links to check out.
- https://www.geeksforgeeks.org/mvc-framework-introduction/#
- https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller

### oneGeneration()

The `oneGeneration()` method implements the rules of Conway's Game of Life as described below.  The method `oneGeneration()` is called automatically over and over once the Run button has been clicked to advance from generation to generation. It can also be paused, resumed, or stepped under user's control.

![GameOfLifePicture1 (1)](https://github.com/user-attachments/assets/8fe5784c-5f6c-4652-b79f-e515bed5f936)
![GameOfLifePicture1 (2)](https://github.com/user-attachments/assets/6f22559f-d5d1-4d8d-97b5-d86ba8bae01e)
![GameOfLifePicture1 (3)](https://github.com/user-attachments/assets/8761b38f-db46-4312-ad2a-ffc60131dced)

### Sources

This starter code was created by Kimberly Jans. Original solution with graphics based on work by Roger Frank from Ponderosa High School in Parker, CO
