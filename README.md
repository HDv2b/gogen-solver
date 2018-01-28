# gogen-solver

Gogen is a solo game presented on a 5x5 grid, with a letter revealed in the first, middle and last columns and rows. A list of words is given and the player solves the puzzle by filling in the remaining 16 cells to fit the words onto the grid, traversing horizonally, vertically, or diagonally to adjascent cells. Each letter can only appears once on the grid.

My local paper has a daily Gogen, and I've mastered the process of solving them, hence I thought I'd try coding a script to apply my technique to solve the puzzles automatically.

## Installation

Standard `npm install`

## Try it out

See the samples folder for an example of how to prepare data to be solved in JSON format. Remember to use "_" (underscores) in place of empty cells.

`npm run solve game_name` - don't include the file extension as this is auto-appended. eg: `npm run solve ES_2018-01-26`