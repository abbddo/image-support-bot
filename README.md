# image-support-bot
A Telegram bot which does google image search for your group.

## Screenshot
![screenshot](http://i.imgur.com/Mse6MsC.jpg)

## Guide
1. Create a Telegram bot and set privacy mode to **False**.
2. Create a custom search engine and get the **API key** and **Search engine ID** (See [https://developers.google.com/custom-search/json-api/v1/overview]()).
3. Create a file named `config.json` at project root with following contents:
```json
{
  "bot": {
    "token": "<Telegram bot api token>"
  },
  "cse": {
    "key": "<google custom search API key>",
    "cx": "<google custom search engine ID>"
  }
}
```
4. run `npm start` to start the bot.
5. Add the bot to your group.
