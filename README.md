<h2 align="center">MIGHTY WARRIOR</h2>

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)  
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

### Bot modular yg bisa membantu kinerja grupmu dengan berbagai fitur lebih

<p align="center">
  <a href="https://github.com/Yunus-ZEND/MightyWarriorBot/fork">
    <img src="https://img.shields.io/github/forks/Yunus-ZEND/MightyWarriorBot?label=Fork&style=social">
    
  </a>
  <a href="https://github.com/Yunus-ZEND/MightyWarriorBot">
    <img src="https://img.shields.io/github/stars/Yunus-ZEND/MightyWarriorBot?style=social">
  </a>
</p>

![Mighty Warrior Logo](https://telegra.ph/file/0a7d20bf46d47ff0438ab.jpg)

### <h3 align="center">DEPLOY KE HEROKU</h3>

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/Yunus-ZEND/MightyWarriorBot"> <img src="https://img.shields.io/badge/Click%20Untuk%20Deploy-green?style=flat&logo=heroku" width="200" height="32.45" /></a></p>

#### class Development(Config):
   - OWNER_ID = 1118936839  # my telegram ID
   - OWNER_USERNAME = "Sur_vivor"  # my telegram username
   - API_KEY = "your bot api key"  # my api key, as provided by the botfather
   - SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost:5432/database'  # sample db credentials
   - MESSAGE_DUMP = '-1234567890' # some group chat that your bot is a member of
   - USE_MESSAGE_DUMP = True
   - SUDO_USERS = []  # List of id's for users which have sudo access to the bot.
   - LOAD = []
   - NO_LOAD = ['translation']
```

If you can't have a config.py file (EG on heroku), it is also possible to use environment variables.
The following env variables are supported:
 - `ENV`: Setting this to ANYTHING will enable env variables

 - `TOKEN`: Your bot token, as a string.
 - `OWNER_ID`: An integer of consisting of your owner ID
 - `OWNER_USERNAME`: Your username

 - `DATABASE_URL`: Your database URL
 - `MESSAGE_DUMP`: optional: a chat where your replied saved messages are stored, to stop people deleting their old 
 - `LOAD`: Space separated list of modules you would like to load
 - `NO_LOAD`: Space separated list of modules you would like NOT to load
 - `WEBHOOK`: Setting this to ANYTHING will enable webhooks when in env mode
 messages
 - `URL`: The URL your webhook should connect to (only needed for webhook mode)

 - `SUDO_USERS`: A space separated list of user_ids which should be considered sudo users
 - `SUPPORT_USERS`: A space separated list of user_ids which should be considered support users (can gban/ungban,
 nothing else)
 - `WHITELIST_USERS`: A space separated list of user_ids which should be considered whitelisted - they can't be banned.
 - `DONATION_LINK`: Optional: link where you would like to receive donations.
 - `CERT_PATH`: Path to your webhook certificate
 - `PORT`: Port to use for your webhooks
 - `DEL_CMDS`: Whether to delete commands from users which don't have rights to use that command
 - `STRICT_GBAN`: Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.
 - `WORKERS`: Number of threads to use. 8 is the recommended (and default) amount, but your experience may vary.
 __Note__ that going crazy with more threads wont necessarily speed up your bot, given the large amount of sql data 
 accesses, and the way python asynchronous calls work.
 - `BAN_STICKER`: Which sticker to use when banning people.
 - `ALLOW_EXCL`: Whether to allow using exclamation marks ! for commands as well as /.
```
<p align="center"><a href="https://t.me/ZendYNS"><img src="https://img.shields.io/badge/My%20Contact%3F-click here-magenta?&style=flat-square?&logo=telegram" width=150px></a></p> <p align="center"><a href="https://t.me/KingUserbotSupport"><img src="https://img.shields.io/badge/Group%20Support%3F-click here-yellow?&style=flat-square?&logo=telegram" width=170px></a></p>

#### anda bisa melihat saya di telegram contoh: [@Mightygrouphelp_bot](https://t.me/Mightygrouphelp_bot)
