# AI for Minesweeper
## Project Title: Minesweeper AI

### Study Program: Bachelors of Science
### Documentation Language: English

### Programming Languages:
Primary Language: Python
Other Languages: Java (a little)

### Algorithms:
Probabilistic Reasoning: For calculating probabilities when the AI encounters uncertain situations (probably using Bayesian inference).
Logical Inference: Used for deducing safe and mine-laden tiles based on the numbers revealed in adjacent tiles.
Minimax Algorithm with Alpha-Beta Pruning: This would used for advanced decision-making where future moves are anticipated.

### Data Structures:
Grid Representation: A 2D matrix representing the Minesweeper board, where each cell holds a value representing a mine, a number, or an uncovered space.
Stacks: For backtracking during the AI's exploration process.
Priority Queue: To prioritize moves with the highest certainty using a probabilistic model.
Sets and Lists: Tracking uncovered tiles, flagged mines, and safe spots.

### Problem Being Solved:
The goal of this project is to develop an AI capable of efficiently playing and solving Minesweeper. The AI will use logical inferences and probabilistic reasoning to reveal safe tiles, flag mines, and solve the game. This AI will handle various board sizes and configurations, navigate uncertainties in the game state, and make decisions when the information is not fully deterministic.

### Inputs:
Board Configuration: The Minesweeper game board, represented as 2D, is generated with a set number of mines and dimensions (e.g., 8x8 grid with 10 mines).
AI Moves: The AI's input is based on the game state (e.g., the revealed tiles and their values), where the AI must select a tile to uncover or flag.

### Usage of Inputs:
The board configuration is used to generate the initial game state, where mines are placed randomly, and adjacent tile numbers are computed.
The AI uses the revealed tiles to infer possible mine locations and to calculate probabilities for uncovering safe tiles.
The AI's decision-making process relies on the input of revealed numbers and the logical deductions made from those numbers (e.g., "if a 1 is next to a flagged tile, then the remaining adjacent tile must be safe").
