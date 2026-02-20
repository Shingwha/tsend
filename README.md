# tsend

> Zero-config CLI tool for sending files via Telegram

## Features

- **Simple** - Just `tsend send file.pdf` and it's done
- **Zero-config** - Works out of the box, no setup required
- **Multiple files** - Send multiple files at once
- **Profiles** - Manage multiple Telegram bots easily
- **Captions** - Add descriptions to your files

## Prerequisites

Before using tsend, you need a Telegram bot:

1. Talk to [@BotFather](https://t.me/BotFather) on Telegram
2. Send `/newbot` and follow the instructions
3. Save the bot token (e.g., `123456789:ABCdefGHIjklMNOpqrsTUVwxyz`)
4. Send a message to your bot, then visit `https://api.telegram.org/bot<TOKEN>/getUpdates` to get your chat ID

## Installation

### Method 1: Git Clone

Navigate to your skills directory, then clone:

```bash
cd path/to/your/skills
git clone https://github.com/Shingwha/tsend.git
```

### Method 2: Manual Download

Visit https://clawhub.ai/Shingwha/tsend to download and extract to your skills directory.

### Method 3: clawhub CLI

```bash
npx --yes clawhub@latest install tsend --workdir path/to/your/workspace
```
