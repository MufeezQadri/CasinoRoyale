# CASINO-ROYAL
A CASINO GAME MADE IN C LANGUAGE
Abstract:

This Application program comprises of three games that one usually comes across in a casino.

They are as follows: 
1] Blackjack
2] Roulette
3] Slots

This program basically asks for your name and then what game will you play, and then satrt of with that game!


The program accepts the choice from the player and then executes the chosen game, by including its functions from header files of the respective games (BlackJack.h, Roulette.h, Slots.h).

The Abstract of the game header files are as follows:
#############    BlackJack.h    #############

This application will function similar to a game of Blackjack. To Start the game you will have to bet chips(minimum 100, maximum no limit(your max chips balance).The dealer will deal 2 Cards to the player and himself (both face up for you, and one face up and one face down to himself). Then according to your cards you can hit, Double the bet, or stand. The commands hit, double and stand would be explained later.

************************************************************
************************************************************

Card Values:

1.  A(Ace) = 1 as well as 11
2.  Face Cards = 10
3.  Numbers holds the same value it shows

************************************************************
************************************************************
The Objective of BlackJack:

Each participant attempts to beat the dealer by getting a count as close to 21 as possible, without going over 21.

How do you beat the dealer?
  -1]By drawing a hand value that is higher than the dealer’s hand value
   2]By the dealer drawing a hand value that goes over 21.
   3]By drawing a hand value of 21 on your first two cards, when the dealer does not.

How do you lose to the dealer? 
  -1]Your hand value exceeds 21.
   2]The dealers hand has a greater value than yours at the end of the round

If the value of you cards (Dealer's and yours) are same, the bet will be pushed(the bet you placed will come back to you)

************************************************************
************************************************************

*Special Case*

SPLITTING CARDS
If a player's first two cards are of the same denomination, such as two jacks or two sixes, they may choose to treat them as two separate hands when their turn comes around. The amount of the original bet then goes on one of the cards, and an equal amount must be placed as a bet on the other card. The player first plays the hand to their left by standing or hitting one or more times; only then is the hand to the right played. The two hands are thus treated separately, and the dealer settles with each on its own merits. With a pair of aces, the player is given one card for each ace and may not draw again.

************************************************************
************************************************************

How To Play:

Our program will be the procedure for the most common blackjack game played with 6 decks. Here is the basic overview of a round of blackjack:

1.Player buys chips
2.Player places a wager
3.Dealer deals cards to players
4.Player decides how to play hand
5.Dealer plays hand
6.Payouts

1. Player Buys Chips
    Before you can play at the table you need chips. Most casinos will not allow “cash plays” wagers anymore, so you will have to let the dealer exchange your money for casino chips. You do this by simply walking up to the table a placing your money on the felt of the table. Do not hand your money to the dealer (they won’t take it). For security reasons dealers cannot take anything out of a player’s hand or vice versa. Once you lay your money on the felt the dealer will lay it out on the table for the cameras to clearly see how much it is and a pit boss will come over and verify the amount. The dealer will count out chip denominations equal to the amount you’ve bought in for and push the chips toward you. You are now free to handle the chips and place your wager. The dealer will arrange your buy-in on the felt so the cameras can clearly see the amount. This is what buying in for $1000 looks like.

2. Player Places a Wager
    At the start of a round the first thing you do is place a bet in the betting circle (sometimes it’s a square, or just a casino logo on the felt where your bet goes). The table will have a small sign on the far right or left side of the table telling you what the betting limits are. Most tables in the US will require a minimum of at least $5 per hand, but the minimum and maximum bet you can make will be different depending on what casino you go to and the regulatory environment where the casino is located.

3. Dealer Deals Cards to Players
    After you place your bet the dealer will deal clockwise, one card, face up, to each player at the table and then one card face down for herself. Then she will deal one more card face up to each player and one more card for herself, face up. Each player has 2 cards, face up, in front of them, but the dealer has one card face up and one face down. It should look something like the picture below. Now it’s time to play the game!

4. Player decides how to play hand
    The dealer will start at the person on their left (also known as “first base”) and wait for that player to play their hand. You have two cards face up in front of your bet. To play your hand, first you add the card values together and get a hand total anywhere from 4 to 21. If you’re dealt a ten-value card and an Ace as your first two cards that means you got a Blackjack! Congratulations! Those get paid 3 to 2 (or 1.5 times your wager) immediately, without playing through the round, as long as the dealer doesn’t also have a Blackjack. If the dealer also has a Blackjack, you wouldn’t win anything but you also wouldn’t lose your original wager. This is called a “push”. If YOU don’t have a Blackjack AND the dealer doesn’t have a blackjack, your dealer will point to each player in succession and wait for you to decide how you want to play your hand. When it’s your turn, you will have to make your decision using the appropriate hand signal. Dealers will not respond to your verbal instructions because the cameras need to see your decisions as well. There are 5 ways you can play your hand:

      a) Stand – If your first two cards are acceptable, you can stand and the dealer will move on to the next player.

      b) Hit – If you would like more cards to improve your hand total, the dealer will deal you more cards, one at a time, until you either “bust” (go over 21) or you choose to stand. There is no limit on the number of cards you can take (other than going over a total of 21).

      c) Double Down – If you have a hand total that is advantageous to you but you need to take an additional card you can double your initial wager and the dealer will deal you only 1 additional card. Note: most casinos will also allow you to “double for less” meaning you don’t have to put up an equal wager to your original wager. However, mathematically speaking there is never a time when doubling for less is a better decision than doubling for the full amount, so we would discourage “doubling for less” even if the casino will let you.

      d) Split – If you’re dealt a pair (2 cards of equal value) you have the option to put out a second wager and the dealer will split the two cards so that each card will become the first card on two new hands. This also applies to face cards. You are allowed to split a hand consisting of a King and a Jack because they both have the same value, even though they are not actually a pair.

      e) Surrender – If you don’t like your initial hand, you have the option of giving it up in exchange for half your original bet back.
  
5. Dealer Plays Hand
		If he has bigger hand than you, and does not cross the value of 21 he wins!




#############    Roulette.h    #############

Roulette is a game played with a large wheel that contains either 37 or 38 pockets. These stops are numbered from 0 to 36, while the American roulette wheel also contains a 00 pocket. All the pockets are all colored; the zeroes are green, while the other spots are evenly divided between 18 red and 18 black pockets.

The dealer spins a ball on the outer rim of the wheel, after which it will eventually fall into one of the numbered spaces. The object for the player is to guess what number the ball will land in.

Before each spin, players have the opportunity to place bets around the roulette table. Players can bet on individual numbers or virtually any combination of numbers.

Once the ball falls into a pocket and rests there, the dealer will call out the winning number as well as the color of the pocket it landed in. Markers are typically used to protect winning bets, after which all losing bets are swept off the table. The dealer will pay all winning bets and, once all of the payouts are completed, players may place bets for the next spin.



************************************************************
************************************************************

Rules of the game:
There are 3 types of bets you can make:
1) Straight-up bet: Choose a single number. High risk, high payout! (35 to 1)
2) Red or black: Choose a color.(1 to 1)
   Red numbers are:  1,3,5,7,9,12,14,16,18,19,21,23,25,27,30,32,34,36
   Black numbers are: 2,4,6,8,10,11,13,15,17,20,22,24,26,28,29,31,33,35
3) Odd or even: Choose odd or even (1 to 1) 

************************************************************
************************************************************

When a winning number and color is determined by the roulette wheel, the dealer will place a marker, also known as a dolly, on that winning number on the roulette table layout. When the dolly is on the table, no players may place bets, collect bets, or remove any bets from the table. The dealer will then sweep away all other losing bets either by hand or rake, and determine all of the payouts to the remaining inside and outside winning bets. When the dealer is finished making payouts, the marker is removed from the board where players collect their winnings and make new bets. The winning chips remain on the board.



#############    Slots.h    #############

This application funtions similar to a game of slots.To start the game you will have to enter you name, and then you will be awared 10,000 chips for starting a new game. Then you have to start and roll. And according to your luck, chips would be awarded.

************************************************************
************************************************************

Reward Pattern:
The pattern on which the winning chips are calculated is selected from the middle line:

1] if you gets triple winning = bet+(bet*0.3)
2] if you gets quad winning = bet+(bet*0.8)
3] if you gets ace winning = bet+(bet*2)
4] if you gets jackpot winning = bet*50


############################################################
Copywrite by Mufeez.
