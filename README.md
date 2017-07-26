# Texas Holdem Poker Ranking System

This project was created to help numerically measure the strength of a poker hand in Texas Holdem. The main difference is that my Poker System is able to figure out the best 5 card score out of the 7 possible cards (Works for 5, 6, r 7. The card system ranks on a score of 9144, which includes Hand Rankings, Number Rankings, and Suit Rankings.

## Future Improvements

The system is by no means perfect. There are still a number of hands (very rare) that may raise issues or incorrectly rank. I am working to fix the system in order to tackle these problems, but for now, it covers more than 99% of them.

I am also working on fixing the run time of the program because it is a fairly greedy algorithm.

The UI of the app is also not the best. Manually entering 5, 6, or 7 cards is tedious and takes a long time while playing an actual game.

I want to use a mathematical system to gauge the likeliness to win based off of a users score. I know the average score, distribution, and probability of getting certain hands. I would like to make a tool based off of that data.

## Rules and Ranking

Rules are taken from World Series of Poker: [WSOP Texas Holdem](http://www.wsop.com/poker-games/texas-holdem/rules/)

Set ranking: Royal Flush, Straight Flush, Four of a Kind, Full House, Flush, Straight, Three of a Kind, Two Pairs, One Pair, High Card

Number ranking: A, K, Q, J, 10, 9, 8, 7, 6, 5 ,4 ,3, 2

Suit ranking: S, H, D, C


## Statistics

Max score: 9144

Average score after 1,000,000 trials was 1626.356483

Test results show a normal distribution with a high center peak skewed to the right

Over 133,784,560 hands for 7 hand poker (52 C 7)
