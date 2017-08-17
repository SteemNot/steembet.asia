# SteemBet.Asia UI
Dice game for Steem | Front-End UI

## HTML GUI

Open index.html in your browser

(use minified [steemjs](https://github.com/pharesim/steemjs), jquery and app.js

## Python server

- requires sqlite to make sql file writeable.

- cp dicedb.txt dicedb.sql

- run .sh script for start


## ChangeLog for this fork:

- [MODIFIED] CSS fixes and edits about front-end login modal/body colors, divs and tags.
- [MODIFIED] Reduced minimum wager to 0.05 ( SteemDice has 0.1 ).
- [MODIFIED] Maximum bets are 50 (Both SBD/STEEM)
- [MODIFIED] SBD as default Currency Bet
- [REMOVED] - Register Steem Link - There is no need for registration because newcomers to steem would have impossible mission to import/deposit funds inside just for playing a dice game.
- [FIXED] - Logo height to 11% so dice is not having a cutout on the bottom.
- [CHANGED] - Complete modifications and translations of platform to Chinese. 
- [UPDATED] - Connecting to wss://steemd.steemitdev.com as fastest blockchain available - Proof of concept available https://ripplerm.github.io/steem-servers/
