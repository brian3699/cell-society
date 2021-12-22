Cell Society
====
## Project Overview

<img width="629" alt="Screen Shot 2021-12-22 at 10 12 50 PM" src="https://user-images.githubusercontent.com/35345069/147098441-5c8b5ac5-97f1-4af7-a284-a888673daeea.png">

This project implements a cellular automata simulator.

I have worked mainly on frontend and controllers. I have significantly contributed to the general design of the project - the roles of controllers and how backend and frontend should interact.

The frontend classes (all classes in the view package and controller package) are well refactored and closely follow the OOP principles. These classes are also versatile and extendable and could be easily used in other projects to create different variations.


## Members and Primary Roles

Young Jun - Frontend Implementation: Controller and View classes, refactoring, algorithm, reflection, testing - everything related to backend.

Haseeb Chaudhry - Backend Implementation:Components, Games; Backend Testing, Documentation, Example File creation, Everything related to backend, Algorithm, Data handling, Structure

Norah Tan - Backend Implementation:Components, Games; Backend Testing, Documentation, Example File creation, Everything related to backend, Algorithm, Data handling, Structure

Ryleigh Byrne - Frontend Implementation: Controller and View classes, refactoring, algorithm, reflection - everything related to backend.


## Timeline

Start Date: 10/11/2021

Finish Date: 11/2/2021

Hours Spent: 150 Hours total. 12-14 hours per person per week.


## Running the Program

Main class: Chooses the language to run the program and instantiates the MainController. The role of Main is kept limited to instantiating the MainController. Running the program is controlled by the controllers.


Data files needed: Data files to run the simulation are dependent on the user however a data file needs to be input in order to run any simulation. Users can create their own data file to input but formatting requires special attention. Outside of the data files, all listed resource files are needed.

Features implemented:
- Run simulation of Game of life
- Run simulation of Spreading Fire
- Run simulation of Segregation
- Run simulation of Percolation
- Run simulation of Wator World
- Create a Grid made of Hexagons, Squares or Triangles
- Stop, Play, Step, Slow down, or Speed up the simulation
- Load multiple simulations
- Replace the current simulation with new simulation
- Show information about the simulation
- Have creation of random csv files and simulation possible
- Change languages
- Change edge policy
- Change neighbor mode
- Change themes
- Read in different file types
- Click on cells to change states


## Notes/Assumptions

Assumptions or Simplifications:

- A specific type of file needs to be input in specific format
- Grid is 2D array only
- Regular shapes as defined by Grid Subclasses are used
- User has certain screen format


Interesting data files:

- GameOfLife: Penta-Decathlon, glider
- SpreadingFire: Multiple Burning Trees sparse forest, one burning tree full forest
- WatorWorld: full sea shark fish, one shark fish world
- Segregation: Random test one
- Percolation: Volcano 

Known Bugs:

- Clicking on certain cells changes other cells in Hexagon grid
- Sometimes the load file doesn’t work because it thinks user has chosen all settings


Noteworthy Features:

- Users can create multiple simulations.
- Users can ultra slow down their simulation
- Clicking on cells is dynamic and create unexpected simulation branch off behaviour
- Grid Expansion in SpreadingFire works (if more time existed could be implemented in creating an infinite grid)
