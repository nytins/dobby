![Dobby](dobby.jpg)

# dobby - the house elf

## Connect to slack from local

1. Go to https://my.slack.com/apps/new/A0F7YS25R-bots and pick a name for the bot.
1. Click `Add integration` and note the bot token.
1. Do below commands to run in local and connect to slack.
1. Bot will then attempt to log into your team, and you should be able talk to it. Try telling your new bot `hello`. It should say `Hello!` back!

```
git clone https://github.com/nytins/dobby
cd dobby
npm install
TOKEN=xoxb-your-token-here npm start
```

## Links

* This project was based on [easy-peasy-bot](https://github.com/slackapi/easy-peasy-bot)
* [Botkit documentation](http://howdy.ai/botkit/docs/).
