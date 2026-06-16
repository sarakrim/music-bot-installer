# 🎵 Telegram Music Bot - One Click Installer

**The easiest way to set up a Telegram music bot in seconds!**

Zero configuration needed - just run one command and you're done!

---

## ⚡ Quick Start (2 Steps)

### Step 1: Clone the project
```bash
git clone https://github.com/sarakrim/music-bot-installer.git
cd music-bot-installer
```

### Step 2: Run the installer
```bash
python3 install.py
```

That's it! The installer will:
- ✅ Check your system
- �� Ask for your bot token (from @BotFather)
- ✅ Install all dependencies
- ✅ Create the bot

Then run:
```bash
python3 music_bot.py
```

---

## 🤖 Get Your Bot Token (1 minute)

1. Open **Telegram** → Search for **@BotFather**
2. Send `/newbot`
3. Choose a name and username
4. **Copy the token** it gives you
5. Paste it into the installer

That's it! 🎉

---

## 📋 What You Need

- **Python 3.8+** (usually pre-installed)
- **FFmpeg** (for audio conversion)
- **Internet connection**

### Install FFmpeg

**Ubuntu/Debian:**
```bash
sudo apt-get install ffmpeg
```

**macOS:**
```bash
brew install ffmpeg
```

**Windows:**
```bash
choco install ffmpeg
```

---

## 🎼 How to Use

Once the bot is running (`python3 music_bot.py`):

1. **Open your bot in Telegram**
2. **Send a music link:**
   ```
   https://www.youtube.com/watch?v=...
   https://soundcloud.com/...
   https://spotify.com/track/...
   ```
3. **Wait for download**
4. **Get your MP3** 🎵

### Bot Commands

- `/start` - Welcome & instructions
- `/help` - Supported platforms
- `/clear` - Delete downloaded files

---

## ✨ Features

🚀 **One-Click Setup** - Fully automated installation  
🎼 **Multi-Platform** - YouTube, SoundCloud, Spotify, TikTok, etc.  
🛡️ **Secure** - Token safely stored, automatic cleanup  
📱 **User-Friendly** - Simple commands, no configuration  
⚡ **Fast** - Instant downloads  

---

## 🐛 Troubleshooting

### "Python not found"
- Install from [python.org](https://www.python.org/downloads/)
- On Ubuntu: `sudo apt-get install python3 python3-pip`

### "FFmpeg not found"
- Run `python3 install.py` again and follow FFmpeg instructions
- Or install manually using commands above

### "ModuleNotFoundError"
- Re-run: `python3 install.py`

### Bot won't start
- Check `token.txt` exists and has valid token
- Try: `python3 music_bot.py`

### Download fails
- Check internet connection
- Try a different link
- Some content might be region-restricted

---

## 📁 What Gets Created

```
music-bot-installer/
├── install.py           ← Main installer (run this!)
├── music_bot.py        ← The bot (run this to start)
├── token.txt           ← Your secret token (auto-created)
├── requirements.txt    ← Dependencies (auto-created)
├── downloads/          ← Temp folder (auto-created)
└── README.md           ← This file
```

---

## 🎯 Next Steps

1. Run the installer: `python3 install.py`
2. Follow the prompts
3. Start the bot: `python3 music_bot.py`
4. Open Telegram and send links to your bot!

---

## ⚠️ Important

- **Never share token.txt** - it controls your bot
- Respect copyright and platform terms of service
- Downloaded files are automatically deleted
- Telegram has a 50MB file limit

---

## 📞 Support

- **Telegram Bot API**: https://core.telegram.org/bots/api
- **yt-dlp**: https://github.com/yt-dlp/yt-dlp
- **Issues**: Create an issue on GitHub

---

## 🎵 Enjoy!

Your music bot is ready. Download and share your favorite tracks! 🎉

**Made with ❤️ for music lovers**
