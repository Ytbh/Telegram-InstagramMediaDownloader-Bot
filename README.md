<h1 align="center">Telegram Bot</h1>
<p align="center">A telegram bot to download media from Instagram! No API Key or Login Needed!<p>

<p align="center">
<a href="https://github.com/simonfarah/Telegram-InstagramMediaDownloader-Bot">
<img src="https://img.shields.io/badge/telegram bot-0088CC?&style=for-the-badge&logo=telegram"></a>

<img src="https://img.shields.io/badge/python-FFD43B?&style=for-the-badge&logo=python">
</p>

<p align="center">
<a href="https://github.com/simonfarah"><img src="https://img.shields.io/badge/author-simon farah-red.svg?style=for-the-badge&logo=github"></a>
</p>

<p align="center">
<img src="https://img.shields.io/github/forks/simonfarah/Telegram-InstagramMediaDownloader-Bot?color=0088CC&style=flat-square">
<img src="https://img.shields.io/github/stars/simonfarah/Telegram-InstagramMediaDownloader-Bot?color=0088CC&style=flat-square">
<img title="Forks" src="https://img.shields.io/github/followers/simonfarah?color=0088CC&style=flat-square">
<img src="https://img.shields.io/badge/maintained-yes-0088CC?&style=flat-square">
</p>

## Requirements
* You must have python installed (of course)
* You must install the following modules

      pip install python-telegram-bot
      pip install requests

## How to use
1. Make sure you installed all the requirements
2. Open Telegram, go to [@BotFather](https://t.me/botfather) and create a new Bot.
3. Copy the Bot Access Token.
4. Open the main.py file using any text editor, go down to line 127 and paste your token there.
5. Save the file and run the script!

## How it works
This bot uses the Instagram public GraphQL API. When a link is sent to the bot, a request to the API is sent and a json response is received. The bot will get every media included in the given post and send it to the user.

## NOTE
Please note that the API requests will not work (aka the bot wouldn't be able to send the media) if you are hosting the bot on a platform like Heroku or PythonAnyWhere. If you are planning to keep the bot running 24/7 you must keep it running on your local machine forever or on a Raspberry Pi. Or just find an alternative API (most of them are paid ones)

## Support My Work
<a href="https://www.buymeacoffee.com/simonfarah" target="blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
