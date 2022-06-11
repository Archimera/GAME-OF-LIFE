# GAME OF LIFE
-Musakhan Eminov & Elmin Mammadov

The Game of Life is, in reality, a cellular automaton defined in 1970 by the English
mathematician John Conway in order to try to solve a problem raised by a
mathematician, father of computer science, John Von Neumann. It is not strictly
speaking a game: it does not require the intervention of a human player, except
to fix the initial conditions of the game. It consists of a universe in which live cells
evolve according to rules precise evolution. In the original version described by
John Conway, the universe is defined on a two-dimensional grid, of variable size,
where each cell is a cell that can take two different states: dead or alive. The
transition from one state to another is guided by the following rules of evolution:

• A dead cell at time t becomes alive at time t + 1 if and only if it has exactly
3 living cells in its vicinity.

• A living cell at time t remains alive at time t + 1 if and only if it has exactly 2
or 3 living cells in its vicinity, otherwise it dies.

• All other cells dies

• The neighborhood used is the 8-neighborhood: for a given cell, its neighbors
are the 8 cells that surround it


# Execution
  1. Create 'build' folder in themain directory
  2. Change directory to the 'build'
  3. Run the 'ccmake ../' command
  4. Run the 'make' command
  5. Execute program using './mygame'  (--see "howtorun")
