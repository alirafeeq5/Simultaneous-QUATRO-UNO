# Simultaneous-QUATRO-UNO
There are two players, and each one gets 4 cards, a "4", a "3", a "2", a "1". Each player orders his or her four cards into a pile. Then repeatedly both players reveal their leftmost card. The lower card is taken away from the pile, thrown away, and the higher one, the winning one, remains in the pile.


How to Play
1.	Select Your Cards:
   
    •	Click on the buttons labeled with numbers (1, 2, 3, 4) to select your cards. You must select exactly 4 cards.
3.	Start the Game:
   
    •	Once you've selected your cards, click the "Start Game" button to begin the game against the computer.

4.	Game Outcome:
    •	The game will simulate each round based on your and the computer's card selections.
    •	The payoff matrix determines the outcome of each round.
    •	The game ends when one player runs out of cards.
    •	A message will display the winner of the game (either you or the computer).

Rules and Payoff Matrix

The payoff matrix is defined as follows:

  •	Each combination of player's card and computer's card has associated payoffs.
  
  •	Payoffs are represented as (Player's Payoff, Computer's Payoff).
  
  •	Game rules include specific outcomes for certain card combinations (e.g., if both select the same card, if one card beats another).

    
This game requires the following dependencies:
    •	tkinter (for GUI)
    •	openpyxl (for exporting the payoff matrix to an Excel file)
    
How to Run
To run the game:

1.	Ensure you have Python installed on your system.
2.	Install the required dependencies (tkinter, openpyxl).
3.	Run the Python script.
4.	Follow the on-screen instructions to play the game.

