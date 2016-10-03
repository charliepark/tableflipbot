# tableflipbot
The simplest Slack bot.

## /tableflip

So you want a slash command for your Slack team so you can enter in
`/tableflip` and have `(╯°□°)╯︵ ┻━┻` show up? This is the repo for you.

----

### Easy Option 1

1. Swing by https://my.slack.com/apps/new/A0F82E8CA and create a new slash command:
  - **command:** /tableflip
  - **URL:** https://wherecanigetsalt.com/tableflip
  - (the rest doesn't really matter)

That's it. Yay.

----

### Easy (Better) Option 2

1. Take index.php file from this repo (https://github.com/charliepark/tableflipbot/blob/master/index.php) and stick it on a server of your own.
2. Swing by https://my.slack.com/apps/new/A0F82E8CA and create a new slash command:
  - **command:** /tableflip
  - **URL:** {the path to your own server / file}
  - (the rest doesn't really matter)
