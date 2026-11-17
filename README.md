<h1 align="center">ᴡᴀɪꜰᴜ ɢʀᴀʙʙᴇʀ ʙᴏᴛ</h1>

<p align="center">
  <img src="https://files.catbox.moe/bvsut6.jpg" width="260"/>
</p>

<p align="center">
<a href="https://github.com/Akatsumo/WaifuGrabberBot/fork">
  <img src="https://img.shields.io/github/forks/Akatsumo/WaifuGrabberBot?style=for-the-badge&color=000000&labelColor=000000">
</a>
<a href="https://github.com/Akatsumo/WaifuGrabberBot/stargazers">
  <img src="https://img.shields.io/github/stars/Akatsumo/WaifuGrabberBot?style=for-the-badge&color=000000&labelColor=000000">
</a>
</p>

---

A competitive Telegram anime collecting game.  
Grab random waifus, grow your collection, trade smartly, and rise through the global leaderboard.

---

<h2 align="center">ᴅᴇᴘʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ</h2>

---

<p align="center">
<a href="https://heroku.com/deploy?template=https://github.com/Akatsumo/WaifuGrabberBot">
  <img src="https://img.shields.io/badge/Deploy%20to%20Heroku-000000?style=for-the-badge&logo=heroku&logoColor=white">
</a>
</p>

---

<h2 align="center">ᴅᴇᴘʟᴏʏ ᴏɴ ᴠᴘꜱ ꜱᴇʀᴠᴇʀ</h2>

---

<p align="center">
<a href="#vps-deployment">
  <img src="https://img.shields.io/badge/Deploy%20on%20VPS-000000?style=for-the-badge&logo=linux&logoColor=white">
</a>
</p>

<details id="vps-deployment">
<summary><b>Click to View VPS Deployment Commands</b></summary>

<br>

```bash
sudo apt update && sudo apt upgrade -y
```

```bash
sudo apt install python3 python3-pip git -y
```

```bash
git clone https://github.com/Akatsumo/WaifuGrabberBot.git
cd WaifuGrabberBot
```

```bash
pip3 install -r requirements.txt
```

Create `.env` file:

```
API_ID=
API_HASH=
BOT_TOKEN=
OWNER_ID=
SUDO_IDS=
MONGO_DB=
GEMINI_KEY=
SUPPORT_CHANNEL=
```

Run the bot:

```bash
python3 -m Grabber
```

Optional 24/7 uptime:

```bash
screen -S waifu
```

```bash
tmux
```

</details>

---

<h2 align="center">ᴜꜱᴇʀ ᴄᴏᴍᴍᴀɴᴅꜱ</h2>

---

| Command | Description |
|---------|------------|
| `/grab` | Grab a random waifu |
| `/animes` | View anime collections |
| `/mywaifus` | View your collection |
| `/gift` | Gift a waifu |
| `/trade` | Secure trade system |
| `/harem` | View selected lineup |
| `/leaderboard` | Global ranking |
| `/changetime` | Adjust spawn cooldown |
| - `/marry` | Marry  waifu from your collection |
| - `/divorce` | Divorce your currently married waifu. |
| - `/chatwaifu` or `Waifu` |  chatting with your waifu. |
| - `/clear` |  clear chatting waifu old data. |

---

<h2 align="center">ᴍᴀꜱᴛᴇʀ ᴄᴏᴍᴍᴀɴᴅꜱ</h2>

---

| Command | Description |
|---------|------------|
| `/addwaifu` | Add waifu to system |
| `/stats` | View bot statistics |
| `/broadcast` / `/announce` | Global announcement |
| `/delete` | Remove waifu |

---

<h2 align="center">ꜰɪɴᴀʟ ɴᴏᴛᴇ</h2>

---

Built for anime communities who enjoy collecting and competing.  
Fork it, improve it, and help expand the multiverse.
