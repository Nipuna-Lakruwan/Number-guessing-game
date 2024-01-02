# Number-guessing-game
The provided C++ code implements a simple number guessing game. Here's an overview of how the code works:

1. Variable Declarations:
   - `int num`: Holds the randomly generated number that the user needs to guess.
   - `int guess`: Stores the user's input guess.
   - `int tries`: Keeps track of the number of attempts the user has made, initialized to zero.

2. Random Number Generation:
   - Seeds the random number generator using the current time.
   - Generates a random number between 1 and 100 and assigns it to the variable `num`.

3. User Interaction in a Do-While Loop:
   - Displays the title of the number guessing game.
   - Enters a do-while loop that continues until the user correctly guesses the number.
   - Inside the loop, prompts the user to enter a guess between 1 and 100 and increments the `tries` counter.

4. Checking the Guess:
   - Compares the user's guess with the randomly generated number (`num`).
   - Provides feedback to the user if the guess is too high, too low, or correct.

5. Congratulations Message:
   - Displays a congratulatory message if the user correctly guesses the number.
   - Includes the number of tries it took the user to guess correctly.

6. End of the Game:
   - Displays a message indicating the end of the number guessing game.

7. Return Statement:
   - Returns 0 to indicate successful execution.

This code creates an engaging and interactive game where the user attempts to guess a randomly generated number within a specified range. The loop ensures that the user can make multiple guesses until they correctly identify the number.
