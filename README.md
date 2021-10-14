### This is only for mine use use main repo. 



<p align="center"><a href="https://t.me/MR_JINN_OF_TG"><img src="https://telegra.ph//file/aff077680944610cb1e6c.jpg" width="5000"></a></p> 
<h1 align="center"><b>NESRIYA-GUARD 🇮🇳 </b></h1>
<h4 align="center">A Powerful, Smart And Simple Userbot In Pyrogram.</h4>


## Support 🚑
<a href="https://t.me/FridaySupportOfficial"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="https://t.me/fridayOT"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>

## Inspiration & Credits
* [Userge-X](https://github.com/code-rgb/USERGE-X/contributors)
* [Userge](https://github.com/UsergeTeam/Userge)
* [Pokurt](https://github.com/UsergeTeam/Pokurt)
* [Pyrogram](https://github.com/pyrogram/pyrogram/contributors)

## Code Owners
* [Chsaiujwal](https://github.com/chsaiujwal)
* [Aditya](https://github.com/Aditya-XD)
* [Lakhac](https://github.com/Lakhac)
* [InukaAsith](https://github.com/InukaAsith)
* [SHRE-YANSH](https://github.com/SHRE-YANSH)

# String Session - Pyrogram 🖱
### Repl 🧨
[![Run on Repl.it](https://repl.it/badge/github/MR-JINN-OF-TG/NESRIYA-GUARD)](https://replit.com/@MRJINNOFTG/TG-SESSION)
### Locally 🏆
```
$ git clone https://github.com/MR-JINN-OF-TG/NESRIYA-GUARD
$ cd FridayUserbot
$ python(3) string_gen.py
```

# Hosting 🖥

### Deploying To Heroku ⚙

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/MR-JINN-OF-TG/NESRIYA-GUARD)

### DEPLOY TO RAILWAY 

[!Deploy to Railway](http://railway.app/new/template?template=https://github.com/MR-JINN-OF-TG/NESRIYA-GUARD&envs=STRINGSESSION,LOG_GRP,API_HASH,API_ID,BOT_TOKEN,LOAD_UNOFFICIAL_PLUGINS,TZ,MONGO_DB&STRINGSESSIONDesc=Get+session+from+here+https://replit.com/@MRJINNOFTG/TG-SESSION&LOG_GRPDesc=A+Group+ID+Where+You+Want+To+Log+Important+Logs.&API_HASHDesc=Get+this+value+from+my.telegram.org&API_IDDesc=Get+this+value+from+my.telegram.org&BOT_TOKENDesc=Get+Your+Bot+Token+From+@BotFather.&LOAD_UNOFFICIAL_PLUGINSDesc=Write+True+or+False+only&TZDesc=Your+Time+Zone.+For+India+write+Asia/Kolkata&MONGO_DBDesc=Get+your+mongodb+url+from+here+cloud.mongodb.com) 

### Self-hosting (For Devs) ⚔
```sh
# Install Git First // (Else You Can Download And Upload to Your Local Server)
$ git clone https://github.com/MR-JINN-OF-TG/NESRIYA-GUARD
# Open Git Cloned File
$ cd FridayUserbot
# Install All Requirements 
$ pip(3) install -r requirements.txt
# Create local.env with variables as given below
# Start Bot 
$ python(3) -m main_startup
```


### Mandatory Configs 📒
```
[+] Make Sure You Add All These Mandatory Vars. 
    [-] API_ID:   You can get this value from https://my.telegram.org
    [-] API_HASH :   You can get this value from https://my.telegram.org
    [-] STRINGSESSION : Your String Session, You can get this From Repl or BY running String_Gen File Locally
    [-] MONGO_DB : Your Mongo DB DataBase Url. 
    [-] LOG_GRP: Your Log Group/Channel Chat ID. This is Very Important and Some Modules Will Not Work Well Without This!
[+] The NESRIYA-GUARD will not work without setting the mandatory vars.
```

# Examples - Plugins 👊

### Plugins 🔧

```python3
from main_startup.core.decorators import friday_on_cmd
from main_startup.helper_func.basic_helpers import edit_or_reply

@friday_on_cmd(['helloworld'],
    cmd_help={
    "help": "This is A TEST",
    "example": "{ch}helloworld"
    })
async def hello_world(client, message):
    mg = await edit_or_reply(message, "`Hello World! This Works!`")
```
### Custom Filters 📣

```python3
from main_startup.core.decorators import listen

@listen(filters.mentioned)
async def mentioned_(client, message):
    await message.reply_text("`Hello World! By The Way Why Did You Mention Me?`")
```

# X-Tra Plugins 🎸
* Please Visit [Xtra-Plugins](https://github.com/MR-JINN-OF-TG/NESRIYA-GUARD-XTRA-PLUGINS) To Checkout Xtra-Plugins.


# Licence 📋
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

* Copyright (C) 2020-2021 by MR-JINN-OF-TG@Github, < https://github.com/MR-JINN-OF-TG >.

FridayUserbot is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 
