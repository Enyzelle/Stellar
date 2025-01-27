<div align="center">

# 🌟 Stellar Bot

<img src="assets/logo.png" alt="Stellar Bot Logo" width="200"/>

*A powerful Discord bot with advanced moderation, auto-roles, logging, and utility features!*

[![Discord.js](https://img.shields.io/badge/Discord.js-v14-blue.svg?logo=discord&logoColor=white)](https://discord.js.org)
[![Stars](https://img.shields.io/github/stars/Enyzelle/stellar-bot?style=social)](https://github.com/Enyzelle/stellar-bot/stargazers)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-v16+-green.svg?logo=node.js&logoColor=white)](https://nodejs.org)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Enyzelle/stellar-bot/graphs/commit-activity)
[![Discord](https://img.shields.io/discord/1323234949481893908?color=7289da&logo=discord&logoColor=white)](https://discord.gg/7YkWDEgdr9)

[Invite Bot](https://discord.com/oauth2/authorize?client_id=1323186196289163284&scope=bot&permissions=416619490374) • [Support Server](https://discord.gg/7YkWDEgdr9)

</div>

---

## ✨ Features

### 🛡️ Advanced Moderation
- **Complete Member Management**: Ban, kick, timeout, warn
- **Message Control**: Bulk delete, slowmode
- **Anti-Raid Protection**: Join rate limiting, account age checks
- **Auto-Moderation**: Spam prevention, bad word filtering
- **Case Management**: Track and manage all moderation actions

### ⚙️ Server Management
- **Welcome System**: Customizable welcome messages and cards
- **Logging System**: Track all server activities
- **Reaction Roles**: Self-assignable roles
- **Auto-Roles**: Automatic role assignment

### 🔧 Utility Features
- **Server Statistics**: Detailed server and user information
- **Role Management**: Role information and management
- **Channel Controls**: Channel information and settings
- **Custom Embeds**: Create beautiful embedded messages

## 📚 Commands

<details>
<summary>🛡️ Moderation Commands</summary>

| Command | Description | Permission |
|---------|-------------|------------|
| `/ban` | Ban a member | `BAN_MEMBERS` |
| `/unban` | Unban a member | `BAN_MEMBERS` |
| `/kick` | Kick a member | `KICK_MEMBERS` |
| `/timeout` | Timeout a member | `MODERATE_MEMBERS` |
| `/warn` | Warn a member | `MODERATE_MEMBERS` |
| `/case` | View case information | `MODERATE_MEMBERS` |
| `/purge` | Bulk delete messages | `MANAGE_MESSAGES` |
| `/massban` | Ban multiple users | `BAN_MEMBERS` |

</details>

<details>
<summary>⚙️ Configuration Commands</summary>

| Command | Description | Permission |
|---------|-------------|------------|
| `/welcome` | Configure welcome system | `MANAGE_GUILD` |
| `/autorole` | Configure auto roles | `MANAGE_ROLES` |
| `/logging` | Set up logging channels | `MANAGE_GUILD` |
| `/automod` | Configure auto moderation | `MANAGE_GUILD` |
| `/reactionrole` | Create reaction roles | `MANAGE_ROLES` |

</details>

<details>
<summary>🔧 Utility Commands</summary>

| Command | Description | Permission |
|---------|-------------|------------|
| `/serverinfo` | View server information | `None` |
| `/userinfo` | View user information | `None` |
| `/roleinfo` | View role information | `None` |
| `/channelinfo` | View channel information | `None` |
| `/avatar` | View user avatars | `None` |
| `/botinfo` | View bot statistics | `None` |
| `/ping` | Check bot latency | `None` |
| `/server` | View server icon or banner | `None` |
| `/help` | View help command | `None` |
| `/invite` | Invite the bot to your server | `None` |

</details>

## 🚀 Getting Started

### Prerequisites
- Node.js 16.9.0 or higher
- MongoDB database
- Discord Bot Token

### Quick Start

1. Clone the repository

```bash
git clone https://github.com/Enyzelle/stellar-bot.git
```

2. Install dependencies

```bash
cd stellar-bot
npm install
```

3. Configure the bot:

```bash
cp config.example.json config.json
```

4. Start the bot

```bash
npm start
```

## ⚙️ Configuration

```json
{
  "token": "YOUR_BOT_TOKEN",
  "clientId": "YOUR_CLIENT_ID",
  "guildId": "YOUR_GUILD_ID",
  "mongoUri": "YOUR_MONGODB_URI",
  "supportServer": "YOUR_SUPPORT_SERVER_INVITE",
  "botInvite": "YOUR_BOT_INVITE_LINK",
  "status": {
    "interval": 10000,
    "activities": [
      {
        "type": "PLAYING",
        "text": "/help | {servers} servers"
      },
      {
        "type": "WATCHING",
        "text": "over {users} users"
      },
      {
        "type": "LISTENING",
        "text": "{commands} commands"
      },
      {
        "type": "COMPETING",
        "text": "discord.gg/support"
      }
    ]
  }
} 
```

## 🎨 Features Preview

<div align="center">
<img src="assets/preview/moderation.png" alt="Moderation" width="400"/>
<img src="assets/preview/welcome.png" alt="Welcome" width="400"/>
</div>

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

- Discord: [yz.yuriza](https://discord.com/users/1317482100290752604)
- Email: [enyz.contact@gmail.com](mailto:enyz.contact@gmail.com)
- Instagram: [@enyzelle](https://instagram.com/enyzelle)
- Support Server: [Join Here](https://discord.gg/7YkWDEgdr9)

## 📋 Planned Features

- [ ] Music system with high-quality playback
- [ ] Custom playlist support
- [ ] Web dashboard
- [ ] Advanced statistics tracking
- [ ] More fun commands

## 💖 Support

If you find Stellar Bot helpful, please:
- Give it a ⭐ star on GitHub
- Join our [support server](https://discord.gg/7YkWDEgdr9)
- Share it with your friends

---

<div align="center">

Made with ❤️ by [Enyzelle](https://github.com/Enyzelle)

</div>
