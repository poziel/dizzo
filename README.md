# Dizzo – The All-in-One Discord Bot 🎯🎵💬

Dizzo is a **multi-purpose Discord bot** designed to replace popular bots like MEE6, Dank Memer, and standalone music bots, by merging their best features into a single, streamlined package.  
It’s built to make managing, moderating, and engaging your Discord community effortless and fun — all while rewarding active members with an **activity-based economy**.

---

## ✨ Key Features

- **Advanced Moderation Tools**  
  Ban, kick, mute, warn, and manage roles with customizable commands.  
  Includes auto-moderation to detect spam, profanity, and rule-breaking behavior.

- **Fun & Social Commands**  
  A mix of meme-style entertainment commands and community engagement tools to keep members chatting and laughing.

- **Integrated Music Bot**  
  Join voice channels, play music from various sources, manage playlists, and control playback with simple commands.

- **Activity-Based Economy**  
  Earn currency through activity and engagement in the server.  
  Spend it in a virtual shop on items, roles, and fun perks.  
  Keep members motivated to participate!

- **League of Legends Custom Game Tools**  
  - Automatically split players into teams for custom matches.  
  - Create temporary channels for each team.  
  - Move players into the correct voice channels instantly.

- **Utility Commands**  
  Helpful commands for information, server management, and quick tasks.

---

## 🛠️ Tech Stack

- **Language:** JavaScript / TypeScript (Node.js)  
- **Frameworks & Libraries:** Discord.js, Prisma (for database), Music streaming integrations  
- **Database:** PostgreSQL or MySQL  
- **Hosting:** Any Node-compatible hosting service (Heroku, Railway, VPS, or self-hosted)  

---

## 🚀 Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/dizzo.git
cd dizzo

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# Edit the .env file with your Discord bot token, database credentials, etc.

# 4. Run the bot
npm run start
```

---

## ⚙️ Configuration

- **Bot Token:** Obtain from the [Discord Developer Portal](https://discord.com/developers/applications).  
- **Database:** Set up PostgreSQL or MySQL and configure connection details in `.env`.  
- **Permissions:** Ensure the bot has the proper permissions in your Discord server (administrator recommended for full feature access).  

---

## 📌 Roadmap

- [ ] Add dashboard for managing bot settings via web interface.  
- [ ] Expand mini-games and interactive economy features.  
- [ ] More integrations for popular games and APIs.  

---

## 🤝 Contributing

We welcome pull requests and feature suggestions!  
Fork the repo, make your changes, and submit a PR.

---

## 📜 License

This project is licensed under the MIT License — see the LICENSE file for details.
