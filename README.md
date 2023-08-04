Guess The Number Game - HunchIt

Upon looking at this brief, the first thing we can do is to start breaking it down into simple actionable tasks for this game, in as much of a logical mindset as possible:

1. Generate a random number between 1 and 100.

2. Record the turn number the player is on. Start it on 1.

3. Provide the player with a way to guess what the number is.

4. Once a guess has been submitted first record it somewhere so the user can see their previous guesses.

5. Next, check whether it is the correct number.

6. If it is correct:
   -Display congratulations message.
   -Stop the player from being able to enter more guesses (this would mess the game up).
   -Display control allowing the player to restart the game.

7. If it is wrong and the player has turns left:
   -Tell the player they are wrong and whether their guess was too high or too low.
   -Allow them to enter another guess.
   -Increment the turn number by 1.

8. If it is wrong and the player has no turns left:
   -Tell the player it is game over.
   -Stop the player from being able to enter more guesses (this would mess the game up).
   -Display control allowing the player to restart the game.

9. Once the game restarts, make sure the game logic and UI are completely reset, then go back to step 1.

How To Play HunchIt:

* Enter the Guess between 0 to 100 and "Submit your Guess". 
* You have 10 tries before you lose!
* Each time your guess is incorrect, you get one less chance for next round.
* After each attempt, you'll be told if your guess was higher/lower than actual answer.
* If you Failed to answer correctly with in 10 tries, !!!GAME OVER!!!
* If you want to replay then "Start New Game" it will reset a new random number.
* When you win, you'll receive an alert telling you "Congratulations! You got it right!".




