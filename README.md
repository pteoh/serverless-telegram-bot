# Queercon Bot

This project was forked off pabluk's sample code. Now with 200% moar Queery for use on [Queercon](https://queercon.org)-related Telegram channels. It mostly serves silly responses for various keywords from the channel.

# Serverless Telegram Bot

A basic serverless [Telegram bot](https://core.telegram.org/bots) using [Google Cloud Functions](https://cloud.google.com/functions/).

This bot runs with Python 3.7 and [python-telegram-bot](https://python-telegram-bot.org/).

See https://seminar.io/2018/09/03/building-serverless-telegram-bot/ for more details about this bot.

## Deploy

```
$ gcloud beta functions deploy webhook --set-env-vars "TELEGRAM_TOKEN=000:yyy" --runtime python37 --trigger-http
```
