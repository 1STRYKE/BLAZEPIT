🔥 Blaze Pit
Multipurpose Discord Bot (Moderation • Games • Leveling • Voice Lock)
Blaze Core is a powerful open-source Discord bot built using discord.py.
It includes moderation tools, fun mini-games, a leveling system, and automatic voice channel locking.
Designed to be simple, expandable, and community-ready.
🚀 Features
🛡 Moderation
blaze kick @user
blaze ban @user
Permission-based access control
Server-safe command handling
🎮 Fun Games
blaze rps rock/paper/scissors
blaze roll
Lightweight and fast response system
📊 Leveling System
XP gained automatically per message
Level progression formula
blaze level to check stats
blaze daily for daily XP reward
JSON-based storage (easy to upgrade to database)
🎤 Voice Channel Lock
Automatically joins a specific voice channel on startup
Auto-rejoins if disconnected
Designed for persistent presence
Works on cloud hosting (Koyeb / Railway / VPS)
⚙️ Installation
1️⃣ Clone Repository
Bash
''' git clone https://github.com/1STRYKE/blazepit.git '''
cd blaze-core
2️⃣ Install Requirements

Bash
pip install -r requirements.txt
3️⃣ Create Environment Variable
Create .env file:

DISCORD_TOKEN=your_bot_token_here
Or set environment variable in your hosting provider.
4️⃣ Configure IDs
Inside bot.py, update:
Copy code
Python
GUILD_ID = YOUR_SERVER_ID
VOICE_CHANNEL_ID = YOUR_VOICE_CHANNEL_ID
Enable Developer Mode in Discord to copy IDs.
5️⃣ Run Bot
Bash
python bot.py
🔐 Required Bot Permissions
In Discord Developer Portal:
Enable:
MESSAGE CONTENT INTENT
SERVER MEMBERS INTENT
PRESENCE INTENT (optional)
In Server Role:
Connect
Speak
Kick Members
Ban Members
View Channel
🧠 Tech Stack
Python 3.10+
discord.py
PyNaCl (voice support)
JSON storage (level system)
📂 Project Structure

blaze-pit/
│
├── bot.py
├── levels.json
├── requirements.txt
└── README.md
🔥 Future Expansion Ideas
XP-based role rewards
Anti-spam auto moderation
Music system
AI integration
Database upgrade (SQLite / MongoDB)
Slash command support
Modular Cogs system
🤝 Contributing
Pull requests are welcome.
Feel free to fork, improve, and expand Blaze Core.
📜 License
MIT License (Recommended for open source projects)
👑 Author
Built by 1STRYKE .
Community-powered development.
