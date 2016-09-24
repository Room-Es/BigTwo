# BigTwo
An Android application for the card game "Big Two"

## How to Play:

### Objective:
The goal of the the game is to be the first player to get rid of all your cards.  If you cannot be the first player without any cards, other placings are determined by whoever has the least amount of cards left.


### Rules:
The game starts by dealing the whole deck of cards evenly between all four players.  Whatever player has the card with the lowest value (3♦) will go first, and must play that card in their first hand.

#### Hands
There are four different hands a player can play.
+ Singles
  + Any random card
+ Doubles
  + Two cards with the same number
+ Triples
  + Three cards with the same number
+ Five Card Hands (Poker Hands)
  + Straight
    + Five cards in order, no suit significance
  + Flush
    + Five cards of the same suit
  + Full House
    + One triple and one double
  + Four of a Kind
    + Four matching cards with one extra card on the side
  + Straight Flush
    + A straight with all cards in the same suit

The value of each hand is determined by the highest card being played (and the type of hand for quintuples).
The value is first determined by the numbers in this order:

3 → 4 → 5 → 6 → 7 → 8 → 9 → 1 0 → J → K → Q → A → 2

For two cards with the same number, the higher value is determined by the suit in this order:

♦ → ♣ → ♥ → ♠

For five card hands, the hand value is determined similarly to poker, where hand value is ordered as such:

Straight → Flush → Full House → Four of a Kind → Straight Flush

To compare to of the same five card hands, the highest value card in the hand will determine the value.  It should be noted that the only card that can be played at the end or beginning of a straight is a 2.

#### Playing the Game

After the cards are dealt, people take turn putting down hands in a counter clockwise direction.  You have to play the same type of hand as the initial hand of the round.  Each round is completed once either every person skips, or the highest possible value is played.
