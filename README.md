# 🔐 AutoWhitelisterDC

**AutoWhitelisterDC** is a Minecraft-Discord integration plugin that allows players to **whitelist themselves** on your Minecraft server directly through your **Discord bot** — no need for admins to whitelist manually!

---

## 🎯 Features

- ✅ Whitelist players from Discord using a simple command  
- ✅ Fully automated — no need to touch your server console  
- ✅ Secure and customizable command handling  
- ✅ Lightweight and efficient (built with Paper API & JDA)  
- ✅ Supports Minecraft 1.20.4+  
- ✅ Prevents duplicate usernames and impersonation  
- ✅ Supports confirmation messages and embed responses  
- ✅ Great for public Discord communities and whitelisted servers

---

## 🚀 Getting Started

### 1. ✅ Requirements

- Minecraft server (Paper 1.20.4+)
- Discord bot token
- Java 17+
- Internet connection

---

### 2. 📦 Installation

1. Download the latest `autowhitelisterdc-1.0-SNAPSHOT.jar`
2. Place it into your `/plugins` directory
3. Start your Minecraft server (or restart if running)
4. The plugin will auto-generate its config

---

### 3. ⚙️ Configuration

After the first run, a config file will be created inside:

Example:

```yaml
bot-token: "YOUR_DISCORD_BOT_TOKEN"
command-prefix: "!"
allowed-roles:
  - "Whitelister"
whitelist-command: "whitelist add %username%"
confirmation-message: "You have been successfully whitelisted!"
💡 Make sure to replace "YOUR_DISCORD_BOT_TOKEN" with your actual bot token and adjust roles as needed.
