![Image](https://graph.org/file/9901c2070cea11d1aa194.jpg)

# WAIFU & HUSBANDO CATCHER 

![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)<br> [![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)<br>
[![Support Group!](https://img.shields.io/badge/Join%20Group-↗-green)](https://t.me/collect_em_support)

_**Available On Telegram As 
[Collect Em all](https://t.me/Collect_em_AllBot) and**_  
_Ask for Help in our [Support Chat](https://t.me/Collect_em_support)_

---

## 📖 About The Repository
● This is an Open Source Implementation of Character Catcher Bot for Telegram.  
● For Example, Grab/Hunt/Protecc/Collect etc.. These Types of Bot you must have seen it on your telegram groups..  
● This bot sends characters in group after every 100 Messages Of Groups. Then any user can guess that character's Name using `/guess` Command.  

We used **Python-Telegram-Bot v20.6** and a little bit of **Pyrogram**.  

---

Use rarity number accordingly:

| Number | Rarity     |
|--------|------------|
| 1      | ⚪️ Common |
| 2      | 🟣 Rare   |
| 3      | 🟡 Legendary |
| 4      | 🟢 Medium |

---

## 👥 User Commands
- `/guess` - Guess the character  
- `/fav` - Add a character to favorites  
- `/trade` - Trade a character with another user  
- `/gift` - Gift a character to another user  
- `/collection` - Boast your harem collection  
- `/topgroups` - List the groups with biggest harem (globally)  
- `/top` - List the users with biggest harem (globally)  
- `/ctop` - List the users with biggest harem (current chat)  
- `/changetime` - Change the frequency of character spawn  

---

## 🔧 Sudo User Commands
- `/upload` - Add a new character to the database  
- `/delete` - Delete a character from the database  
- `/update` - Update stats of a character in the database  

---

## 👑 Owner Commands
- `/ping` - Pings the bot and sends a response  
- `/stats` - Lists number of groups and users  
- `/list` - Sends a document with list of all users that used the bot  
- `/groups` - Sends a document with list of all groups that the bot has been in  

---

## 🚀 Deployment Methods

### 🔹 Deploy to Heroku (Easy)

1. Click the button below to deploy directly on **Heroku**:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/<YourUsername>/WAIFU-HUSBANDO-CATCHER)

2. After deployment, open your Heroku app → **Settings** → **Config Vars** and add the following:

| Variable Name  | Example Value | Description |
|----------------|---------------|-------------|
| `BOT_TOKEN`    | `123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11` | Bot token from BotFather |
| `API_ID`       | `1234567` | Telegram API ID (from [my.telegram.org](https://my.telegram.org)) |
| `API_HASH`     | `abcdef1234567890abcdef1234567890` | Telegram API hash |
| `GROUP_ID`     | `-1001234567890` | Numeric group ID where bot works |
| `DATABASE_URL` | `postgres://...` | Postgres DB URL (Heroku Postgres addon) |

3. Scale your worker:
```bash
heroku ps:scale worker=1
### Local Deploy/VPS
- Fill variables in [`config.py`](./shivu/config.py) 
- Open your VPS terminal (we're using Debian based) and run the following:
```bash
sudo apt-get update && sudo apt-get upgrade -y           

sudo apt-get install python3-pip -y          
sudo pip3 install -U pip

git clone https://github.com/<YourUsername>/WAIFU-HUSBANDO-CATCHER && cd WAIFU-HUSBANDO-CATCHER

pip3 install -U -r requirements.txt          

sudo apt install tmux && tmux          
python3 -m shivu
```       
 
## License
The Source is licensed under MIT, and hence comes with no Warranty whatsoever.

## Appreciation
If you appreciate this Code, make sure to star ✨ the repository.

## Developer Suggestions 
- Don't Use heroku. Deploy on Heroku is just for testing. Otherwise Bot's Inline will Work Too Slow.
- Use a reliable VPS provider
