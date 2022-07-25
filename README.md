# Chess Engine AI

A javascript chess engine AI built for a fun side project

## About

Uses minimax algorithm optimized with alpha-beta pruning, and board evaluation with piece square tables like in [Sunfish.py](https://github.com/thomasahle/sunfish).

Goal of the project was only to develop an AI decision making algorithm, GUI and mechanics implemented with [Chessboard.js](https://github.com/oakmac/chessboardjs) and [Chess.js](https://github.com/jhlywa/chess.js) respectively. 

Idea and algorithm concept explanations from this guide: https://www.chessengines.org/

## How to Play

Playable at https://ljoks.github.io/chess-ai/

Play as white by dragging a piece to a desired location. AI will play as black and use minimax algorithm at a search depth of your choice using the drop down below the board. A higher search depth will play a more accurate move, but take longer to decide.

Refresh the page to reset the board.

## TODO
[x] Board and Gui
[x] Evaluation Function
[x] Minimax algorithm implementation
[x] Alpha-Beta pruning optimization
[] Quiescence Search
[] Move Ordering
[] Memoization of move evaluation
