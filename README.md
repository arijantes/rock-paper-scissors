The user would like a simple game, where users can play rock, paper, scissors against a computer. The user should be able to pick "rock", "paper", or "scissors" then see if they win! If they input something other than "rock", "paper", or "scissors", the computer should refuse to play. Users also need to be able to see the score and quit the game. 

After meeting with the client, you've worked out together and agreed upon the following requirements: 

The computer should start out by asking the user to type "r", "p", "s" (for "rock", "paper", or "scissors", respectively), "x" (which shows the score) or "q" (for "quit") at the command line.
If they enter an "r", "p", or "s", it will reveal whether it chose rock, paper, or scissors, and who won. A point then gets added to the appropriate players' score (both start at 0).

Of course, the computer should choose randomly, and without considering what the user chose, because that would be cheating.
If a "q" is entered the computer should show the score and quit the Ruby process, returning control to the command line.
If an "x" is entered, the computer should show the score and prompt the user again for input.
If the user enters an invalid input, the computer should show an error message and ask the user to enter again.
