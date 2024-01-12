Project: Memory IQ Game
This game was developed using HTML,CSS,and Javascript.
Developed By:
Ajith Kumar S
Prabakaran K
Syed Sulthan J
Senthil Kumar N S

If you play this game, click on the link.
output shown on the website
Website link: https://memorycardtc.netlify.app/
Game Rules: 
1. All the cards are shuffled and placed face down on a flat.
2. The player flips over two cards. If the two cards match, the player keeps them and takes another turn, if the cards do not match,
the player flips them back over, and it becomes the next player's turn.
3. The game continues in this way with players taking turns flipping over two cards at the time until all the cards have been matched.
The player with the most matches at the end of the game is decared the winner.

Implementation Algorithm:
Step 1: Each emoji is given a code. Time counter is set on when game commences.
Step 2: For each click on the card the emoji is set visible using mouse event.
Step 3: The opened card emoji code is compared with consequent next opening emoji from another card.
Step 4: If both are same, card visibility is made true. Static variable counter is incremented, which was initially 0.
Step 5: Else card visibility is false. 
Step 6: Game completes when counter variable becomes 8(totally 16 squares in our game).


