# ChannelBan

This Discord bot watches specific channels and **automatically bans any user who posts in them**, unless they have one of the ignored roles.  
All configuration is done through a simple `.env` file.

---

## ⚙️ Features
- Watches specific channels (configurable in `.env`)
- Bans users who post there
- Optionally ignores users with certain roles
- Sends error reports to a webhook (optional)
- Deletes 7 days of the banned user’s messages
- Written in **Node.js** using [`discord.js`](https://discord.js.org/)

---

## 🔑 Required Discord Intents
Make sure the bot has the following:
- **Server Members Intent**
- **Message Content Intent**

In the guild, it also needs:
- View Channels  
- Read Message History  
- Moderate Members  
- Ban Members  

---

## 🚀 Setup

```bash
git clone https://github.com/yourusername/channelban.git
cd channelban/
cp .env.example .env
