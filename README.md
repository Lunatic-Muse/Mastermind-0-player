# Mastermind-0-player
I created a text based version of mastermind, and then created an algorithm to play it.
Mastermind works by having 1 player create a secret code, made of pins each with 6 possible colors (I changed colors to numbers). A second player tries to guess what the secret code is, and each time player 1 grades, for each pin that is the right color and in the right spot there is a black pin, of the remaining for each pin that is the right color but in the wrong spot there is a white pin.
The code works by taking all possible combinations and randomly selecting one, then based on the grade, removes all impossible combinations.
I then changed the amount of pins from 4 to 6 to see how it affected how many guesses it would take to get the right answer.
