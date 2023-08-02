# minesweeperAI
## Background
Minesweeper is a puzzle game that consists of a grid of cells, where some of the cells contain hidden “mines.” Clicking on a cell that contains a mine detonates the mine, and causes the user to lose the game. Clicking on a “safe” cell (i.e., a cell that does not contain a mine) reveals a number that indicates how many neighboring cells – where a neighbor is a cell that is one square to the left, right, up, down, or diagonal from the given cell – contain a mine.

## Description
The program utilizes a knowledge base and inference to find the most likely solutions in Minesweeper. Once a cell is clicked, the knowledge base is represented as a set containing all neighboring cells and information about the number of mines in those cells. The knowledge-based agent first clicks on a cell randomly until it can guarantee a safe move inferred from its knowledge base.

## Getting Started
The program is run using the command-line argument `python runner.py`
