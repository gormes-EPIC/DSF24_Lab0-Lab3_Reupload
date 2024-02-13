# Lab 0: Mastermind
For this lab, you will create a Python program to play Mastermind in the terminal. Upload your final game in a file 'mastermind.py' with comments to this Classroom assignment to submit.

**Rubric**
- 4 points - Complete mastermind.py file that runs the game with at least the basic functionality as described above. Code should include appropriate comments
- 3 points - Program fulfills some but not all of the requirements specified above
- 2 points - Incomplete or missing

## Objective
In the game Mastermind, one player, the codemaker,  creates a secret code the other player, the codebreaker, must discover their code in as few moves as possible. The secret code consists of 4 pegs, ordered left to right. Each peg can be one of six colors. Then each turn the codebreaker will make a guess of what the secret code is. The codemaker will then tell them which pegs, if any, are both the correct color and in the correct location and which pegs are the correct color but in the wrong location. Think how Wordle colors tiles green, yellow, or grey. The codemaker continues making guesses until they get to the correct answer. There are many variations on the rules, like deciding to incorporate duplicate colors. Typically a game will take about eight to twelve turns but if you play optimally you can win with a worst case scenario of 6 turns.



## Basic Functionality
For full credit, your program must...The computer will randomize a code of 4 colors, the player will make guesses, and the computer will respond accordingly. When the game ends, ask the player if they would like to play again.
A few rounds of play might look something like this:
```
Guess: GPBY
\_!!\*

Guess: PBRY
\*!!\*
```

The pegs use the following shorthand:
- R-Red
- O-Orange
- Y-Yellow
- G-Green
- B-Blue
- P-Purple

The responses use the following shorthand:
- \* - correct color and location
- ! - correct color, incorrect location
- \_ - neither



## Advanced Functionality(Optional)
Other functionality you could include menus that allow you to skip or explain the rules, options to include/exclude duplicate colors, options for <6 or >6 pegs or custom pegs, a limitation on the number of turns, a two player mode where you are able to enter your own codes, etc.

## Resources
- [Wikipedia Article](https://en.wikipedia.org/wiki/Mastermind_(board_game))
- [Link to play the game](https://mastermindgame.org/)


