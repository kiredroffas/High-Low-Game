This program plays a High-Low game with the user. The range of numbers to play with by default is 1-100 (if "./highlow" is entered on cmd line).
If "./highlow #" is entered on cmd line its changes the range of numbers to play with to 1-#. The user is then welcomed, and taught the rules 
and controls of highlow (unless "highlow #" is entered b/c assumed user already knows how to play). The user then hits any key once they have
decided on a number and want to continue. The program then guesses a number. If the guessed number is too high, user presses 'h', and program 
guesses a lower number. If the guessed number is too low, user presses 'l', and program guesses a higher number. If foul play is detected, the
program echos error message and exits. Otherwise play continues until user presses 'c', meaning that their number was guessed correctly. Program
then prints number of tries it took to guess the number and exit message, and exits. 