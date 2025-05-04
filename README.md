

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

### <br>   ❖ DEPLOY_WORKFLOWS ❖
```
name: Node.js CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]
        # See supported Node.js release schedule at https://nodejs.org/en/about/releases/

    steps:
    # Step to check out the repository code
    - uses: actions/checkout@v2

    # Step to set up the specified Node.js version
    - name: Use Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v2
      with:
        node-version: ${{ matrix.node-version }}

    # Step to install dependencies
    - name: Install dependencies
      run: npm install

    # Step to run the bot with the correct port
    - name: Start the bot
      env:
        PORT: 8080
      run: npm start
```





--------------
 
### <br>   ❖ DEPLOY_HEROKU ❖

`🚀 IF YOU WANT TO DEPLOY 𝗜𝘀𝗹𝗮𝗺𝗶𝗰𝗸 𝗰𝗵𝗮𝘁 𝗯𝗼𝘁  ON HEROKU SO FIRST GET  THIS BLUE BUTTON [DEPLOY TO HEROKU] THEN YOU CAN ENJOY THIS BOT 🚀`

------------
 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new-app?template=https://github.com/cyber-ullash/CYBER-BOT-COMMUNITY)

----------

### <br>    ❖ DEPLOY_REPLIT ❖

`🚀 IF U HAVE YOUR REPLIT ACCOUNT SO YOU CAN EASY DEPLOY 𝗜𝘀𝗹𝗮𝗺𝗶𝗰𝗸 𝗰𝗵𝗮𝘁 𝗯𝗼𝘁  ON REPLIT CLICK BLACK BUTTON [DEPLOY TO REPLIT] AND FIND CONFIG.JSON FILE THEN MONGODB KEY THEN RUN CODE AND ENJOY BOT 🚀`

-------------

<p align="left"><a href="https://repl.it/https://github.com/cyber-ullash/CYBER-BOT-COMMUNITY"> <img src='https://img.shields.io/badge/-REPLIT-orange?style=for-the-badge&logo=replit&logoColor=white'/></a>

--------------

### <br>   ❖ DEPLOY_KOYEB ❖

`🚀 IF YOU HAVE YOUR KOYEB ACCOUNT SO YOU CAN DEPLOY 𝗜𝘀𝗹𝗮𝗺𝗶𝗰𝗸 𝗰𝗵𝗮𝘁 𝗯𝗼𝘁  ON KOYEB WITH EASY SETUP 🚀`

---------

<a href='https://app.koyeb.com/services/deploy?type=git&repository=https://github.com/cyber-ullash/CYBER-BOT-COMMUNITY&branch=main&name=ISLAMICK-CYBER-MIRAI-BOT&builder=dockerfile&env[OWNER_NUMBER]=01859551262%3B%E2%9D%A3%EF%B8%8F&env[MODE]=public&env[PREFIX]=&env[antidelete]=false&env[ANTI_LINK]=false&env[AUTO_STICKER]=false&env[AUTO_VOICE]=false&env[AUTO_REPLY]=false&env[STATUSLIKES]=true&env[ALIVE_MSG]=CYBER+IS+ONLINE&env[BOT_NAME]=ISLAMICK CYBER CHAT &env[HEART_REACT]=true%F0%9F%8E%97%EF%B8%8F%E2%9D%A3%EF%B8%8F&env[ANTI_BAD]=false&env[AUTO_READ_STATUS]=false&env[AutoReaction]=false&env[SESSION_ID]=' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/-KOYEB-blue?style=for-the-badge&logo=koyeb&logoColor=white'/></a>

------------

### <br>  ❖ DEPLOY_RAILWAY ❖

`🚀 IF YOU HAVE YOUR RAILWAY ACCOUNT SO YOU CAN DEPLOY 𝗜𝘀𝗹𝗮𝗺𝗶𝗰𝗸 𝗰𝗵𝗮𝘁 𝗯𝗼𝘁   ON RAILWAY WITH EASY SETUP NOTE:-MAYBE SOME PROBLEM TO DEPLOY ON KOYEB I ILL FIX SOON 🚀`

--------

<a href='https://railway.app/new' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/RAILWAY-h?color=black&style=for-the-badge&logo=railway'/></a></p>

---------------

### <br> ❖ MORE DEPLOY METHOD ❖

--------
### <br>   ❖ DEPLOY_GLITCH ❖

<a href='https://glitch.com/signup' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/GLITCH-h?color=pink&style=for-the-badge&logo=glitch'/></a></p>

--------

### <br>   ❖ DEPLOY_CODESPACE ❖

<a href='https://github.com/codespaces/new' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/CODESPACE-h?color=navy&style=for-the-badge&logo=visualstudiocode'/></a></p>

--------

### <br>   ❖ DEPLOY_RENDER ❖

<a href='https://dashboard.render.com' target="_blank"><img alt='DEPLOY' src='https://img.shields.io/badge/RENDER-h?color=maroon&style=for-the-badge&logo=render'/></a></p>

-----------
`🚀 HOW TO DEPLOY 𝗜𝘀𝗹𝗮𝗺𝗶𝗰𝗸 𝗰𝗵𝗮𝘁 𝗯𝗼𝘁  ON WORKFLOWS FREE GITHUB WATCH VIDEO 🚀`

-------------

<p align="center">
   <a href="https://youtu.be/qHUMWc7CTS8?si=GcGts8mTsEWbDJ1o"><img src="https://i.ibb.co/71mYRh4/116-1161192-podcast-subscribe-listen-button-youtube-sign-hd-png.png" alt="Watch tutorial on YouTube" border="0"  width="105">
    </a>
</p>

-------------
Dᴏɴ’ᴛ Fᴏʀɢᴇᴛ ᴛᴏ ɢɪᴠᴇ ᴀ sᴛᴀʀ ⭐️ ᴀꜰᴛᴇʀ ꜰᴏʀᴋ
