# Telegram Video Player Bot (Beta)
[![Bot Updates](https://img.shields.io/badge/VideoPlayerBot-Updates%20Channel-green)](https://t.me/Deepu_the_editor)
[![Bot Support](https://img.shields.io/badge/VideoPlayerBot-Support%20Group-blue)](https://t.me/deepu_the_editor)

An Telegram Bot By [@Deepuz](https://github.com/Deepu-000) To Stream Videos in Telegram Voice Chat.

## Main Features

- Supports Live Streaming
- Supports YouTube Streaming
- Supports Live Radio Streaming
- Supports Video Files Streaming
- Supports YouTube Live Streaming
- Customizable Userbot Protection (PM Guard)

## Deploy Own Bot

### Railway (Reommanded)
<p><a href="_"><img src="https://img.shields.io/badge/Deploy%20To%20Railway-blueviolet?style=for-the-badge&logo=railway" width="200""/></a></p>

### Heroku (Don't Complain)
<p><a href="https://heroku.com/deploy?template=https://github.com/Deepu-000/fuckingstrem.git"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

## Commands (Botfather)
```sh
start - Start The Bot
help - Show Help Message
radio - Start Radio Streaming
stream - Start Video Streaming
stopradio - Stop Radio Streaming
endstream - Stop Video Streaming
```

## Config Vars
1. `API_ID` : User Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : User Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather XD
4. `BOT_USERNAME` : Your Telegram Bot Username, get it from @Botfather XD
4. `SESSION_STRING` : Pyrogram Session String of User Account, get it from [@genStr robot](http://t.me/genStr_robot) or [![genStr](https://img.shields.io/badge/repl.it-genStr-yellowgreen)](https://repl.it/@AsmSafone/genStr)
5. `CHAT_ID` : ID of Channel/Group where the bot will works or stream videos.
6. `AUTH_USERS` : ID of Users who can use Admins commands (for multiple users seperated by space).
7. `REPLY_MESSAGE` : A reply to those who message the USER account in PM. Leave it blank if you do not need this feature.

## Requirements
- Python 3.6 or Higher.
- [Telegram API key](https://docs.pyrogram.org/intro/quickstart#enjoy-the-api).
- Latest [FFmpeg Python](https://www.ffmpeg.org/).
- Pyrogram [String Session](http://t.me/genStr_robot) of the account.
- The User Account Needs To Be An Admin In The Channel/Group.

## Self Host
```sh
$ git clone https://github.com/Deepu-000/fuckingstrem.git
$ cd VideoPlayerBot
$ sudo apt-get install python3-pip ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
# <create .env variables appropriately>
$ python3 main.py
```


## License
```sh
VideoPlayerBot, Telegram Video Chat Bot
Copyright (c) 2021  Deepu <https://github.com/AsmSafone>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
```

## Credits

- [Me](https://github.com/Deepu-000) for [Fuck](https://github.com/Deepu-000/fuckingstrem.git) ????
- [Fuck](https://github.com/Deepu-000) for [Pyrogram](https://github.com/pyrogram/pyrogram) ??????
- [shit](https://github.com/Deepu-000) for [pytgcalls](https://github.com/MarshalX/tgcalls) ??????
