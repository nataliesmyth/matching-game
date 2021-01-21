## Memory Matching Game!

User flips over cards using clicks to find matching pairs.
If the user flips a card and then it's sibling, the cards disappear, if the cards don't match, both will flip over when another card is picked.
Game is over when the timer runs out

## Game Requirements
When the game starts, a timer starts and the cards are shuffled/randomized
cards disappear if you click matching cards ONLY if all other cards are facedown
If two cards are face up, clicking a 3 card should hide the first two cards and keep card 3 face up
Player should be able to PAUSE, RESTART, and QUIT the game at any time.
If the user finds all the pairs before timer runs out, user wins, otherwise they lose
When game ends, add a congrats message for the winner, and a better luck next time message for the loser

## BREAK DOWN THE PROBLEM
CARDS
-create cards
    use UL
-grab cards in the DOM and push them to a new array
-randomize array
display the cards face-down
