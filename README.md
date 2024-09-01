# Copyright-ProtectBot 🤖

[![GitHub issues](https://img.shields.io/github/issues/Vishal-1756/Copyright-ProtectBot)](https://github.com/Vishal-1756/Copyright-ProtectBot/issues)
[![GitHub stars](https://img.shields.io/github/stars/Vishal-1756/Copyright-ProtectBot)](https://github.com/Vishal-1756/Copyright-ProtectBot/stargazers)
![GitHub license](https://img.shields.io/github/license/Vishal-1756/Copyright-ProtectBot)

## Overview 🚀

**Copyright-ProtectBot** is a powerful Telegram bot designed to protect the copyright of media shared in groups by automatically deleting them after 1 hour. It also provides functionalities to enable or disable media deletion on a per-group basis and includes various commands for bot management and monitoring.

## Features 

- **Automatic Media Deletion**: Deletes all media (photos, videos, animations, documents) in the group after 1 hour.
- **Enable/Disable Media Deletion**: Group admins can enable or disable the auto-deletion feature.
- **Its Also Delete Edited Messages**: Its make sure edited messages don't cause copyright strikes.

## Installation and Usage 🚦

#### Prerequisites

- Python 3.7+
- [Telegram API ID & Hash](https://my.telegram.org) and [Bot Token](https://t.me/BotFather)

#### 1. Clone the repository:

```bash
git clone https://github.com/Vishal-1756/Copyright-ProtectBot.git
cd Copyright-ProtectBot
```

#### 2. Set up environment variables:

Create a `.env` file in the root directory and add the following:

```env
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
BOT_USERNAME=your_bot_username
```

#### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

#### 4. Run the bot:

```bash
python copyright.py
```

#### 5. Deploy to StackHost (Optional):

<div align="left">
  <a href="https://t.me/StackHost">
     <img src="https://graph.org/file/7e91d83f67d20f158cfdc.jpg" alt="Deploy On StackHost" width="150" />
  </a>
</div>

## Commands List 📋

- `/ping` or `/speed`: Check the bot's response time.
- `/start` or `/help`: Display the bot's introduction message.
- `/anticopyright [enable|disable]`: Enable or disable the media deletion feature for a group (admin only).
- `/stats`: Show the total number of groups, users, and other statistics.
- `/restart`: Restart the bot (developer only).

## How It Works 🛠️

1. **Media Deletion**: The bot tracks all media shared in a group and schedules their deletion after 1 hour.
2. **Group Management**: Admins can use the `/anticopyright` command to enable or disable media deletion for their group.
3. **Bot Monitoring**: Developers can restart the bot or check its statistics using the provided commands.

## Contributing 🛠

Feel free to fork the repository, make improvements, and submit pull requests. Open issues if you encounter any bugs or have feature requests.
