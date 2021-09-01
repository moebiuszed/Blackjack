# Blackjack
A text-based blackjack game, with all features from classic blackjack for the whole family!

# The game
Everyone's favourite! The rules are simple, the play is thrilling and you can use all the strategies you want!
Nobody is going to be mad at you ;).
You can play with as many friends as you want!

Default and custom mode

You will be presented with an option to choose, play with the default game rules or your own custom ones. 
Options are:
- Minimun bet: represents the minimun bet each participant has to make at the start of each game
- Funds: how much money each player have at available
- Croupier show card: by default, croupier will show its first card, while second one is revealed when its turns begins.

By default:
- Minimun bet: 5¢
- Funds: 100¢
- Croupier show card

Number of players

After the rules are set, you'll be asked how many participants will be playing this session. It affects how many packs of cards are. Minimun is one, maximun is up to your PC.
You don't have to remember which number you are. The script will ask for your name and everytime it's your turn, it will use said name.
 

The Pack

The standard 52-card deck is used and, depending on the number of players, several decks could be shuffled together. Yes, if there is only one deck, there will be only one Ace of Spades, as it should be!
The program will remember cards between games, if all Aces are gone, they're gone untill the game reshuffles decks.
When there are less than n number of cards left, it will be indicated with a prompt and it will be time for the cards to be reshuffled.

Object of the game

Each participant attempts to beat the dealer by getting a count as close to 21 as possible, without going over 21.

Card values/Scoring

Aces can be 1 or 11, when the player hit s (for stand), the game will pick the highest value without going over 21.
If a participant draws 'Ace of Spades' and 'Eight of Hearts', it will be displayed both values, 9 and 19; if, for example,
'five of Clubs' is drawn next, only 14 will be displayed, as 24 is over 21.
Face cards are 10 and any other card is its pip value.

Betting

Before the deal begins, each player places a bet. Minimun bet, by default, is 5, and maximun is the player's available money.

The deal

When all players have placed their bets, each player receive two cards, croupier too. All cards will be shown except croupier's second one.

Naturals

If a player's first two cards are an ace and a "ten-card" (a picture card or 10), giving a count of 21 in two cards, this is a natural or "blackjack." If any player has a natural and the dealer does not, the dealer pays that player one and a half times the amount of their bet. If the dealer has a natural, they immediately collect the bets of all players who do not have naturals, (but no additional amount). If the dealer and another player both have naturals, the bet of that player is a stand-off (a tie), and the player takes back his bet.

If the dealer's face-up card is a ten-card or an ace, they look at their face-down card to see if the two cards make a natural. If the face-up card is not a ten-card or an ace, they do not look at the face-down card until it is the dealer's turn to play.

The play

Order is static, Player 1 allways starts first, and then comes Player 2 and so on. Player must decide whether to "stand" (not ask for another card) or "hit" (ask for another card in an attempt to get closer to a count of 21, or even hit 21 exactly). Thus, a player may stand on the two cards originally dealt to them, or they may ask the dealer for additional cards, one at a time, until deciding to stand on the total (if it is 21 or under), or goes "bust" (if it is over 21). In the latter case, the player loses and the dealer collects the bet wagered. The dealer then asks next player and serves them in the same manner.

The combination of an ace with a card other than a ten-card is known as a "soft hand," because the player can count the ace as a 1 or 11, and either draw cards or not. For example with a "soft 17" (an ace and a 6), the total is 7 or 17.
While a count of 17 is a good hand, the player may wish to draw for a higher total. If the draw creates a bust hand by counting the ace as an 11, the player simply counts the ace as a 1 and continues playing by standing or "hitting" (asking the dealer for additional cards, one at a time).

The Croupier's play

When the dealer has served every player, the dealers face-down card is turned up. If the total is 17 or more, it must stand. If the total is 16 or under, they must take a card. The dealer must continue to take cards until the total is 17 or more, at which point the dealer must stand. If the dealer has an ace, and counting it as 11 would bring the total to 17 or more (but not over 21), the dealer must count the ace as 11 and stand. The dealer's decisions, then, are automatic on all plays, whereas the player always has the option of taking one or more cards.

Splitting pairs

If a player's first two cards are of the same denomination, such as two jacks or two sixes, they may choose to treat them as two separate hands when their turn comes around. The amount of the original bet then goes on one of the cards, and an equal amount must be placed as a bet on the other card. The player first plays the hand #1 by standing or hitting one or more times; only then is the hand to the #2 played. The two hands are thus treated separately, and the dealer settles with each on its own merits. With a pair of aces, the player is given one card, and only one, for each ace and can not draw again. Also, if a ten-card is dealt to one of these aces, the payoff is equal to the bet (not one and one-half to one, as with a blackjack at any other time).

Doubling down

Another option open to the player is doubling their bet when the original two cards dealt total 9, 10, or 11. When the player's turn comes, they place a bet equal to the original bet, and the dealer gives the player just one card. With two fives, the player may split a pair, double down, or just play the hand in the regular way. Note that the dealer does not have the option of splitting or doubling down.

Insurance
When the dealer's face-up card is an ace, any of the players may make a side bet of up to half the original bet that the dealer's face-down card is a ten-card, and thus a blackjack for the house. Once all such side bets are placed, the dealer looks at the hole card. If it is a ten-card, it is turned up, and those players who have made the insurance bet win and are paid double the amount of their half-bet - a 2 to 1 payoff. When a blackjack occurs for the dealer, of course, the hand is over, and the players' main bets are collected - unless a player also has blackjack, in which case it is a stand-off. Insurance is invariably not a good proposition for the player, unless they are quite sure that there are an unusually high number of ten-cards still left undealt.

Settlement

A bet once paid and collected is never returned. Thus, one key advantage to the dealer is that the player goes first. If the player goes bust, they have already lost their wager, even if the dealer goes bust as well. If the dealer goes over 21, the dealer pays each player who has stood the amount of that player's bet. If the dealer stands at 21 or less, the dealer pays the bet of any player having a higher total (not exceeding 21) and collects the bet of any player having a lower total. If there is a stand-off (a player having the same total as the dealer), no ¢ are paid out or collected.

Withdraw

After the game resolution, if any participant would want to withdraw, they can do so by typing their name. The script will recognize the player and deactivate its profile for the remainder of the session.
If any player's funds are below the minimun bet, they're automatically deactivated and if there are no players left, the script will quit by itself.

# Setup

Game is built under pyhton 3.9 and doesn't requiere any special libraries, other than python installed in the system.
You can run the game, in Windows, directly from the bat file or through any other means.
