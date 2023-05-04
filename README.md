# Connect4
Description: The goal of this project is to create a Python-based AI agent that can play Connect-4
with Power-ups against a human player or another AI agent. The game will have the classic
Connect-4 rules, but with the addition of power-ups that can be used strategically by the players.


# Goals go here

Difficulty Levels: Implement different AI difficulty levels (easy, medium, hard) that utilize different search depths or algorithms. This will allow players to choose a challenge that matches their skill level.

Timer: Add a countdown timer for each player's turn, making the game more challenging and intense.

Power-ups: Introduce power-ups that give players advantages, such as removing an opponent's piece, swapping turns, or placing multiple pieces in a single turn.

Power-ups could include (not limited to):

1. Remove a piece:Remove one of the opponent's pieces from the board.
2. Swap positions: Swap the position of two pieces on the board (either the player's own pieces or the opponent's).
3. Double move: Play two pieces in a single turn.
4. Freeze: Temporarily freeze an opponent's piece, preventing them from making any moves in a specific column.
5. Teleport: Move one of your pieces to another location on the board.
6. Undo: Reverse the last move made by either you or your opponent.
7. Protect: Shield one of your pieces from being affected by your opponent's power-ups.
8. Color Swap: Temporarily change the color of a piece on the board, potentially interrupting your opponent's winning streak.

(dont have to use all these powerups


The AI agent should implement its own evaluation function to decide the best moves based on
the current state of the game, taking into account the power-ups available and the overall game
strategy. A simple GUI can be built using Pygame or Tkinter to display the game board and
allow for user interaction. 

Ways to implement power ups

1. just randomly assing it to a player after a specific turn
2. power up drops - the game just randomly drops a power up in a specific spot during the game where a player can just get it.
3. Earn power-ups through gameplay: Players can earn power-ups by achieving specific milestones during the game, such as placing a certain number of pieces on the board or blocking the opponent's winning moves. This approach rewards skillful play and encourages players to think strategically.

