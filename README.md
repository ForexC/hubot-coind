# hubot-coind

A Hubot script that interacts with various cryptocoin daemons.

## Features

* Fully functional and secure tipbot with Rain and Soak.
* Show difficulty, block height, and network hashrate from supported daemons.

## Installation

Requires hubot: https://hubot.github.com/

Clone https://github.com/upgradeadvice/hubot-coininfo/ into hubot/node_modules

Add `"hubot-coind"` to `external-scripts.json`

## Commands
```
hubot address - Get a deposit address
hubot balance - Show your balance
hubot active - Count the channel's active users.
hubot rain <amount> - Rain on the channel's active users.
hubot soak <amount> - Soak the channel with accumulated coins
hubot tip <user> <amount> - Tip a specific user or bot
hubot withdraw <amount> <address> - Withdraw your coins
hubot height - Show block height
hubot hps - Show network hashrate
hubot diff - Show difficulty
hubot about - About this bot

```
## Configuration

Start a coin daemon and let it update.
Edit [`config.sample.json`](config.sample.json)

## Development

TODO

`npm run`

## License

[MIT](LICENSE)

## Author

upgradeadvice
