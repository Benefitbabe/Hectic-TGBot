dinero 
# 𝙃𝙚𝙘𝙩𝙞𝙘 𝘿𝙤𝙬𝙣𝙡𝙤𝙖𝙙𝙚𝙧 𝘽𝙮 𝙈𝙧 𝙁𝙧𝙖𝙣𝙠

![Hectic Downloader](https://dabby.vercel.app/hect.jpg)

A powerful and user-friendly Telegram bot for downloading YouTube videos and audio directly to Telegram.

## 🌟 Features

- 🔍 **YouTube Search** - Search for videos directly within Telegram (top 10 results)
- 🎥 **Multiple Quality Options** - Download videos in 144p, 240p, 360p, 480p, 720p, or 1080p
- 🎵 **Audio Downloads** - Extract MP3 audio from videos
- ⚡ **Direct to Telegram** - Media files sent directly to your chat (no external links)
- 📊 **Real-time Statistics** - Track bot uptime, users, and system performance
- 🎨 **Beautiful Interface** - Clean, modern design with loading animations
- 🧹 **Auto Cleanup** - Automatic message deletion after 60 seconds

## 📋 Commands

| Command | Description |
|---------|-------------|
| `/start` | Start the bot and see the welcome menu |
| `/help` | Display help information |
| `/developer` | View developer contact information |
| `/uptime` | Check how long the bot has been running |
| `/users` | View user statistics |
| `/system` | Display system information (RAM, ping, etc.) |

## 🚀 How to Use

1. **Start the bot** - Send `/start` to begin
2. **Search or paste URL** - Either:
   - Send a YouTube URL directly
   - Send a search query (e.g., "lofi music")
3. **Select video** - If searching, reply with a number (1-10) to select a video
4. **Choose quality** - Pick your preferred video quality or audio format
5. **Receive media** - The bot will upload the media directly to Telegram

## 💻 Installation

### Prerequisites
- Node.js v20 or higher
- Telegram Bot Token (from [@BotFather](https://t.me/BotFather))

### Setup

1. Clone this repository:
```bash
git clone <your-repo-url>
cd hectic-downloader-bot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file:
```env
BOT_TOKEN=your_telegram_bot_token_here
```

4. Run the bot:
```bash
npm start
```

For development with auto-restart:
```bash
npm run dev
```

## 🔧 Configuration

Edit `config.js` to customize:
- Bot name and creator info
- Auto-delete timeout
- Search results limit
- Loading animation frames
- Welcome and help messages

## 📦 Dependencies

- `node-telegram-bot-api` - Telegram Bot API wrapper
- `axios` - HTTP client for API requests
- `youtube-search-api` - YouTube search functionality
- `dotenv` - Environment variable management

## 🎯 Technical Features

- **Caching System** - Efficient video data caching with auto-cleanup
- **Error Handling** - Comprehensive error handling and fallbacks
- **User Tracking** - Anonymous user statistics
- **Memory Management** - Automatic cache cleanup after 5 minutes
- **File Size Handling** - Graceful handling of large files with fallbacks

## 📊 System Requirements

- **RAM**: Minimum 512MB (recommended 1GB+)
- **Storage**: 1GB free space recommended
- **Network**: Stable internet connection required

## ⚠️ Limitations

- Telegram file size limits apply (50MB for non-premium, 2GB for premium users)
- Live streams cannot be downloaded
- Age-restricted or private videos are not supported

## 👨‍💻 Developer

**Mr Frank**
- 📱 Telegram: [t.me/mrfrankofc](https://t.me/mrfrankofc)
- 💻 GitHub: [github.com/mrfr8nk](https://github.com/mrfr8nk)
- 📞 WhatsApp: +263719647303

## 📄 License

MIT License - Feel free to use and modify!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 🙏 Acknowledgments

- YouTube API for search functionality
- Telegram Bot API for the amazing platform
- All users and contributors

---

Made with ❤️ by 𝙈𝙧 𝙁𝙧𝙖𝙣𝙠
