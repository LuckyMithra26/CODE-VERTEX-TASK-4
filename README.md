# CODE-VERTEX-TASK-4
The Rock-Paper-Scissors Game is a fun and classic project that helps in learning basic programming concepts like user input, conditional statements, loops, and randomness. The game involves a competition between the user and the computer, where both make their choices (Rock, Paper, or Scissors), and the winner is determined based on simple rules:

Rock beats Scissors
Scissors beat Paper
Paper beats Rock
The game can be played in a single round or extended for multiple rounds, with optional score tracking for both the user and the computer.

Key Features:
User Input: The user is prompted to choose between Rock, Paper, or Scissors.
Computer Selection: The computer randomly selects its choice from Rock, Paper, or Scissors.
Game Logic: The game determines the winner based on the user’s and computer’s choices.
Display Result: The result is displayed, indicating whether the user won, lost, or the game was a tie.
Score Tracking (Optional): The user’s and computer’s scores are tracked if multiple rounds are played.
Play Again: After each round, the user can choose to play another round.

Code Breakdown:
Importing Modules:

random: The random.choice() function is used to allow the computer to randomly select between Rock, Paper, or Scissors.
Determining the Winner (determine_winner() function):

This function compares the user’s and computer’s choices and applies the game rules:
If both choices are the same, it's a tie.
If the user’s choice beats the computer's, the user wins.
Otherwise, the computer wins.
Displaying the Result (display_result() function):

The user's and computer's choices are displayed on the screen.
The result (win, lose, or tie) is printed.

Main Game Logic (play_game() function):

The program enters a while loop that runs until the user types "quit".
The user is asked to input their choice. If the input is invalid (not "rock", "paper", or "scissors"), it prompts the user to try again.
The computer randomly selects a choice using random.choice(["rock", "paper", "scissors"]).
The game logic determines who wins using the determine_winner() function, and the result is displayed using display_result().
Score Tracking: The user's and computer's scores are updated after each round and displayed at the end of the game.
Play Again:

After each round, the program asks the user if they want to continue. The game will continue until the user types "quit".
Final Score:

When the user quits the game, the final scores are displayed, showing how many rounds were won by the user and how many by the computer.

Code Concepts:
Randomness:

The random.choice() function is used to generate the computer’s move, making each round unpredictable.
Conditionals:

if, elif, and else statements are used to compare the user’s and computer’s choices, determining the game outcome.
Loops:

The while True loop keeps the game running until the user decides to quit by entering "quit".
Input Validation:

Before proceeding with the game, the user's input is validated to ensure they enter a valid option (rock, paper, or scissors).
Score Tracking:

Each time a round is completed, the scores for both the user and the computer are updated and displayed.
