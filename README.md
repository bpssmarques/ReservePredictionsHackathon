# ReservePredictionsHackathon
Functionality


Every 15 minutes, a predictions round will occur. Players will have a 5-minute deposit period followed by 10 minutes of the active game. After 10 minutes, the positions will close rewards will be distributed to the winners from the bets provided by the losers each round. 
The minimum bet users will be able to place will be three rTokens.
Positions can be bullish, neutral, or bearish, accounting for what you believe is the most probable result. A user’s odds and rewards will be calculated based on other players' predictions. 
For example if the predictions are as follows: 1000 dollars on bullish, 500 dollars on neutral, and 2000 dollars on bearish, that will mean should the results come out bullish, the rewards the players in bullish positions receive will be 2500 dollars distributed across all the players with that position plus whatever funds users wagered.
The threshold for a prediction to be neutral is a 0,1% variation over or under the initial price. 
For example, if the price of AVAX is 12,5 dollars, a price variation below or equal to 1.25 cents will be considered neutral.
Should the results of
The following function is responsible for calculating winning rewards:


This game is entirely decentralized, meaning players do not play against “the house” like in traditional casinos, but against each other.
If there is only one player in a specific round, that player will have his funds returned to his wallet, no matter the results of that round.

Deployment Details

The contracts for this protocol were deployed on Avalanche Mainnet as they require the use of Chainlink Price Feeds, and the Ethereum Mainnet gas costs for contract deployment are too high. 
Another issue is the fact that Goerli and Ropsten Testnets do not have price feeds in them, which are integral pieces of the Reserve Predictions Game.


0x215F571F15482673de141f7F43f5624B62f86B46 - DummyToken
0x3b1e4ebf269bcc8fe792ac8e1ce58e9e64e189da - predictions
