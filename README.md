# SteemBet.Asia UI
Dice game for Steem | Front-End UI

## HTML GUI

Open index.html in your browser

(use minified cdn [steemjs](https://cdn.steemjs.com/lib/latest/steem.min.js), jquery, lo-app.js and hi-app.js (lower and higher front-end)

## Dependencies

PIP, Python, Sqlite3, Steem

## Python server

- requires sqlite3 to make sql file writeable.

- sqlite3 dicedb.sql
Copy paste paragraph by paragraph, in sqlite3 terminal from dicedb.txt file
type .quit

- run .sh script for start


## ChangeLog for this fork:

- [MODIFIED] CSS fixes and edits about front-end login modal/body colors, divs and tags.
- [MODIFIED] House-Edge as low as 1% !!!
- [NEW FEATURE] Switch between play hi or play lo dice!
- [MODIFIED] Maximum bets are 50 (Both SBD/STEEM)
- [MODIFIED] SBD as default Currency Bet
- [REMOVED] - Register Steem Link - There is no need for registration because newcomers to steem would have impossible mission to import/deposit funds inside just for playing a dice game.
- [FIXED] - Logo height to 11% so dice is not having a cutout on the bottom.
- [UPDATED] - Connecting to wss://steemd.steemitdev.com as fastest blockchain available - Proof of concept available https://ripplerm.github.io/steem-servers/
