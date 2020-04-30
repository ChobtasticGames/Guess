Hi guys, this is my first README.md so please let me know if I've formatted anything wrong/can improve in any way would be much appreciated thanks!
The project is a basic calculation guessing game where the first block of code represents the "Secret Number" users have to guess the secret number for the console to display a "You Win!" text.
The second important block of code is the 'guessCount' section, this ultimately keeps a count of how many guesses the user has implemented.
Number three is the 'guessLimit' which is set to '3' meaning the user has 3 guesses and only 3 guesses. This can be modified.
The next line of code is a 'bool' variable for C++. Which is equal to a true or false value this becomes active in the next few lines of code.
Underneath the 'bool' variable is a 'While' loop. This connects with the Secretnum condition, stating while the secret number is not equal to the guess, to increment the guess count until the out of guesses limit has been reached, making the bool loop for the needed amount of guesses.
cout = consoleout, prompts the computer.
cin = prompts the user.
After all lines of code prior to this have been terminated, and the guess is wrong, the guessCount increments.
Once the guess is wrong, an 'else' statement will continue the loop until the OutofGuesses is true.
If the OutofGuesses is true, the computer prints out a "You Lose!" text.
Prompting another outcome through another 'else' statement if the guess is correct the computer prints out 'You Win!'
