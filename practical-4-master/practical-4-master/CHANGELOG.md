# CHANGELOG

* v1.1.11 [2019-11-25]: Fixed error where there would be only 2 turns because the check to move to the next player 
  was broken.

* v1.1.10 [2019-11-25]: Fixed error when can discard was not called when looking for all "discarable" cards, meaning all
cards where able to be discarded. This is fixed so that cards are now checked before being labelled "discardable"

* v1.1.9 [2019-11-25]: Fixed error when skip, draw2 and draw4 were not being set to false, meaning 
  skip, draw2 and draw4 would always be true. 

* v1.1.8 [2019-11-21]: Fixed error where cards in normalised form would never change instead of changing
  to show the perspective of whoever's turn it is.

* v1.1.7 [2019-11-21]: Fixed error where king would not change direction of the game.

* v1.1.6 [2019-11-21]: Fixed error where if a 4 was played, 2 cards would be drawn and 
  now when a 2 is played 2 cards are drawn instead.

* v1.1.5 [2019-11-21]: Fixed error in test_can_discard__allows_ace where trying to test a 
  king instead of testing an ace.

* v1.1.4 [2019-11-21]: Fixed error where player could not discard a card of the same suit as card on the top of 
  discard pile.
  Fixed error where player could not discard a card of the same value as card on the top of discard pile 

* v1.1.3 [2019-11-20]: Fixed error when player picked up wrong amount of cards. 
  Changed pick_up_card in switch.py so that the iterator "i" has the correct output when amount of cards are drawn.

* v1.1.2 [2019-11-20]: Fixed syntax in player. Bracket missing in the select card function for smartAI

* v1.1.1 [2019-11-20]: Players are now dealt 7 cards instead of 6.
  Removed second Ace from each suit.
  
* v1.1.0 [2019-11-08]: Added a SmartAI computer opponent.
  Added strategy players.SmartAI
  None of the bugs have been fixed.

* v1.1.0 [2019-10-25]: First major release.
  This version is known to contain some bugs.

  
