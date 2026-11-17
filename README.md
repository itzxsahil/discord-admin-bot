<h1 align="center">🛡️ Discord Server Administration Bot</h1>

<p align="center">
  <a href="https://github.com/itzxsahil">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=5865F2&center=true&vCenter=true&width=900&lines=Advanced+Discord+Server+Administration+Suite;Role-Based+Access+Control+%7C+Slash+Commands;Modular+Server+Settings+%26+Audit+Logging;Engineered+by+itzxsahil" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Discord-py%20v2.0-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <img src="https://img.shields.io/badge/Slash-Commands-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Security-Role%20Gated-orange?style=for-the-badge">
</p>

---

## 📸 Project Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/itzxsahil/discord-admin-bot/main/assets/project-banner.svg" width="100%" alt="Project Preview" />
</p>

---

# 🚀 Overview

A Discord server administration bot featuring permission-gated slash commands, per-guild customization, and security verification.

---

# 🏗️ System Architecture & Data Flow

<p align="center">
  <img src="https://raw.githubusercontent.com/itzxsahil/discord-admin-bot/main/assets/architecture.svg" width="100%" alt="System Architecture &amp; Data Flow" />
</p>

<br>

Discord app commands are received via WebSocket gateway, verified against guild owner IDs and roles in `config.json`, and executed with audit confirmation.

---

# ✨ Features

✅ **Native Slash Commands**: Modern Discord interface support.\n✅ **Role & Owner Security**: Commands strictly protected by Discord role hierarchies.\n✅ **Persistent Guild Settings**: Custom configuration stored per server in `config.json`.

---

# 📦 Installation & Quickstart

```bash
# Configure your token in config.json
pip install -r requirements.txt
python bot.py
```

---

# 👤 Author & Support
- Built with ❤️ by [@itzxsahil](https://github.com/itzxsahil)
- Star ⭐ this repository if you find it helpful!
