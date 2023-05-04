# Discord_casino_bot
## Bot URL
https://discord.com/api/oauth2/authorize?client_id=1080649824665346048&permissions=8&scope=bot

## Command Usage

### gambling game

/blackjack **bet** : play blackjack with the bot, which bets a certain amount of chips.

/war **bet** **invite**: play war game with the bot or other discord users, which bets a certain amount of chips.

### daily quest

/daily: check the daily quest progress; user will get 1000 coins when running the command for the first time every day.

### chips

/chips **user**: check the chips that a specific user has.

/distribute: get extra 50 coins when running the command every 24 hours.

### gifting

/gift **recipient**: send random gift to other user's mailbox

/mailbox: check the gifts in his own mailbox

## Run locally

```console
// go to the root directory of the cloned project
// replace the token using your own discord bot's token

// build
BOT_TOKEN={token} ./gradlew build

// run
BOT_TOKEN={token} ./gradlew run
```