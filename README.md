# *Conway’s Game of Life* Using FPGA
Presented by Gerin Fajardo, Kevin Foyet, Tyler Marts, and Raymond Wong  <br/>
ECE 3300.02 - Digital Circuit Design Using Verilog  <br/>
Professor Mohamed Aly, Ph.D // California State Polytechnic University, Pomona  <br/>

## Demonstration Video
[![thumbnail](https://img.youtube.com/vi/CcwDj1lyKrI/0.jpg)](https://www.youtube.com/watch?v=CcwDj1lyKrI)

## Abstract
> *This abstract is an excerpt from a longer report, the full report can be accessed [here](https://docs.google.com/document/d/1esijIz1XCN74vlpnBnkL7jEymoO07kjb9qlBPdcqF9o).

*Conway’s Game of Life* is a zero-player game where a cellular automaton is played on a 2-dimensional square grid, created by mathematician John Horton Conway in 1970. On this grid, each cell (square) can occupy one of two states, alive or dead, with the general goal being the observation of how the grid of cells evolves as a whole.

Cells live or die based on four rules:
1. Any living cell with fewer than two neighbors dies.
2. Any living cell with more than three living neighbors dies.
3. Any living cell with two or three living neighbors may live unchanged.
4. Any deceased cell with exactly three living neighbors can come to life.

This project report will focus on recreating this game through the use of the Nexys A7 FPGA board, and the hardware description language (HDL) Verilog will be used to program it to follow the game’s rules.

On the Nexys A7 board, eleven of the sixteen switches will be used as an 8-bit speed control, overflow control, enable, and reset. All buttons will be used to control the location of the cursor, as well as a toggle for a cell’s state. Lastly, seven of the eight seven-segment display digits will be used to display the value of the speed and the current generation of the game. As for the visuals, a 16x16 grid will be displayed through a VGA interface on a connected monitor.
