<h1>About the Game</h1>

Mastermind is a two-player code-breaking game where one player, the code-maker, creates a secret code using a series of colored pegs, and the other player, the code-breaker, tries to guess the code within a limited number of attempts. The game typically comes with a board with four rows of holes, where the code-maker places four colored pegs in a specific order, with the possibility of using duplicates.

The code-breaker makes a guess by placing four colored pegs in the same order on the same board. The code-maker provides feedback by placing smaller pegs in either white or black color in the feedback row. A black peg indicates that the code-breaker has guessed the correct color and position, while a white peg indicates that the code-breaker has guessed the correct color but in the wrong position.

The code-breaker then uses this feedback to adjust their next guess, using a process of elimination to deduce the correct code. The game continues until the code-breaker correctly guesses the code or until the maximum number of attempts is reached.

Mastermind is a challenging game that requires logical thinking, deductive reasoning, and strategic planning. It is suitable for players of all ages and can be played in about 5 minutes.


<h1>HOW TO PLAY</h1>

This is a command line interface where the user inputs the first letter of a color that they
wish to play a guess for. The user will be told how many colors of the code that they have
guessed correctly and/or how many colors are placed in the correct position to form the code.

```
git clone https://github.com/chparmley/MasterMInd.git
cd MasterMind
python3 mastermind.py
```