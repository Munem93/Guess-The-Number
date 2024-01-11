The program starts with importing the 'random' module, to generate random numbers according to the task.
It prints the message 'welcome to the game' to greet user.
The program enters an infinite loop using the "while(True) statement to allow users to make multiple guesses.
User prompted to enter their number guesses, then the input converted to an integer using the int(input()) function functionand assign it to the variable "guess".
The program generates a random number between 1 and 100 using the "random.randint(1,100)" function and assigns it to the variable "number".
If generated number is greater than teh user guess ('number>guess') then the program prints "the guess is too low" to indicate that the user guess is too low.
If generated number is less than the user guess ('number<guess') then the program prints "the huess is too high" to idicate that user guess is too high.
If neither of the above conditions met means that user has guessed the correct number and the program prints "Congrats" and this will indicate that user guessed the correct number.
After provideing any feedback on the user guess the program continues to the iteration of the loop and this will allow the user to make more guesses until it reachs the point where user guess is correct.
