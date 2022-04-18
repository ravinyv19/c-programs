# c-programs
programs
In this article, the task is to create a 2- player cricket game where Player 1 is the user operating the program and Player 2 is the computer. In this game, the following series of steps are followed:

First, the program will generate a random number between 0 and 25. That number will be the score that Player 1 needs to make to win this match. Suppose the program-generated random number is 15, then this number will be the score that Player 1 needs to achieve.
The second step is a real match between Player 1(User) and Player 2(Computer).
The user will give input from numbers 1 to 6 using the keyboard. The system will then again generate a random number between 1 and 6. If the input of the user differs from the random number generated by the system, then it is a hit and the user will get the score as the same number that was given as input by the user. If the two numbers match, the user will be out and the final total score will be printed.
The total score scored by the user is the sum of all the numbers entered by the user. The score is calculated after each input by the user. Previous Input + Current Input of the user.
Example:

Random Number generated by System is 15. This is the winning score.

Now Player will enter number between 1 and 6.
Player: 2
System will now generate a random number between 1 and 6.
System: 1
The player is safe he can play further as both numbers are different.

Player will input a random number between 1 and 6.
Player: 3
System will now generate a random number between 1 and 6.
System: 4

This process keeps ongoing till same number is chosen by Player and System

Player: 6

System: 6

Now, as both numbers are same(player’s and system’s) then player is out.

Result: You lose, your total score is 5.

GAME OVER.
