# blackjack
Blackjack Tech Test

Can Macs beat the Dealer at Blackjack (21s)?

### Modelling game

- Create a deck of cards
- Two players (called Macs and Dealer) who will play each other
- Each player receives two cards from the top of the shuffled deck of cards

### Rule implementation
 - Determine the score of hand (Numbered cards score their point value. Jack, Queen and King score 10 and Ace scores 11.)
 - Check if any of the players have blackjack (21) with their starting hand and win the match
 - If no player has Blackjack, Macs can start drawing cards from the top of the deck
 - Macs should stop drawing cards from the deck if his total score reaches 17 or more
 - If Macs's total score becomes higher than 21, then Macs loses
 - When Macs stops drawing, the dealer can start drawing cards from the top of the deck
 - When the Dealer's score is higher than Macs's, the Dealer should stop drawing cards
 - If the Dealer's total score becomes higher than 21, then the Dealer loses
 - Determine which player wins the game
 - Additional challenges (don't give this to the interviewee)
 - Ace scores 1 or 11
