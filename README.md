# AutoDelete-V2
Delete group messages after a specific time

## Variables
1. `API_ID` : Get from [my.telegram.org](https://my.telegram.org/)
2. `API_HASH` : Get from [my.telegram.org](https://my.telegram.org)
3. `BOT_TOKEN` : Your telegram bot token from [@BotFather](https://t.me/BotFather)
4. `SESSION` : Generate from here [![GenerateStringName](https://img.shields.io/badge/repl.it-generateStringName-yellowgreen)](https://repl.it/@subinps/getStringName)
5. `GROUPS` : ID of Groups (seperate by spaces)
6. `ADMINS` : ID of Admins, messages from admins will not delete (seperate by spaces)
7. `TIME` : Time in seconds

### Make sure:
- Bot is admin in Groups with delete permission
- Account used to create SESSION is a member in Groups

## Deploy
You can deploy this bot anywhere.


<summary>Deploy To Heroku</summary>
<br>
<p>
<a href="https://heroku.com/deploy?template=https://github.com/trailerror13/AutoDel">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>

<a href="https://youtu.be/kB9TkCs8cX0">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>


## Deploy in your VPS

```sh
git clone https://github.com/psychokillar/AutoDel
cd AutoDelete-V2
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 bot.py
```

### Credits
- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Arun](https://t.me/Arun_TG)
