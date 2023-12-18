# Random-Number-Game

This C++ program implements a simple console-based Number Guessing Game. The game generates a random number between 1 and 100, and the player is tasked with guessing the correct number. The program provides feedback after each guess, indicating whether the guess is too high or too low.

# How the Game Works

The program generates a random number between 1 and 100 using rand() % 100 + 1.
The user is welcomed to the game with an introductory message.
A do-while loop is used to repeatedly prompt the user for guesses until the correct number is guessed.
After each guess, the program checks if the guess is equal to the randomly generated secret number.
If the guess is correct, a congratulatory message is displayed along with the number of attempts made.
If the guess is too low, the program informs the user to try again with a higher number.
If the guess is too high, the program instructs the user to try again with a lower number.
The loop continues until the user correctly guesses the number.

# Running the Program
To play the game, compile the C++ program and run the executable. The user will be prompted to enter guesses until the correct number is guessed.

# Code Structure
#include Statements: Include necessary libraries for input/output, random number generation, and time.
main Function: The entry point of the program.
Random Number Generation: Generate a random number between 1 and 100.
Game Loop (do-while): Repeatedly prompt the user for guesses until the correct number is guessed.
User Input: Accept user input for guesses.
Feedback Messages: Provide feedback to the user based on the correctness of the guess.
End of Program: Display a congratulatory message when the correct number is guessed and exit the program.

### Example Gameplay
```

Welcome to the Number Guessing Game!
Try to guess the number between 1 and 100.

Enter your guess: 50
Too low! Try again.
Enter your guess: 75
Too high! Try again.
Enter your guess: 60
Too low! Try again.
Enter your guess: 70
Too high! Try again.
Enter your guess: 65
Too low! Try again.
Enter your guess: 68
Too high! Try again.
Enter your guess: 67
Congratulations! You guessed the correct number in 7 attempts.

```
