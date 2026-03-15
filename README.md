<div align="center">

# ⚡ Velyx

**A powerful multipurpose Discord bot focused on antinuke, moderation, automation and more.**

</div>

---

## 🚀 Setup

### 1. Install dependencies
```bash
npm install
```

### 2. Configure environment
Copy `.env.example` to `.env` and fill in your values:
```
TOKEN=your_bot_token
CLIENT_ID=your_client_id
```

### 3. Add your owner ID in `src/config/config.js`
```js
owners: ['YOUR_DISCORD_ID'],
```

### 4. Start the bot
```bash
node src/shard.js
```

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 🛡️ AntiNuke | Full server protection — anti-ban, anti-bot, anti-channel/role delete, and more |
| 🔨 Moderation | Ban, kick, mute, purge, lock, hide, nick, role management |
| 🤖 AutoMod | Automated moderation rules |
| 📋 Logging | Comprehensive server event logging |
| 🔧 Utility | Ping, avatar, banner, serverinfo, userinfo, stats |
| 🎁 Giveaway | Full giveaway system with reaction entry |
| 👋 Welcome | Canvas-based welcome cards |
| 🔊 Join to Create | Dynamic voice channel creation |
| 🎨 Activity Roles | Auto-assign roles based on Spotify/playing/streaming |
| 🎫 AutoRole | Auto-assign roles on member join |
| ⭐ AutoResponder | Keyword-based auto responses |
| 🔁 AutoReact | Auto-react to keyword messages |
| 🔕 Ignore | Per-channel command ignoring with bypass list |
| 🎙️ Voice Control | Lock, hide, rename, limit, ban, transfer your VC |
| 💤 AFK | Global and per-server AFK with ping tracking |
| 📺 Media Only | Restrict channels to media-only content |

---

## ⚙️ Configuration

Edit `src/config/config.js` to set:
- `prefix` — default command prefix (default: `-`)
- `color` — embed color
- `owners` — bot owner Discord IDs
- `links.supportServer` — your support server invite

---

## 📁 Structure
```
src/
├── base/         Velyx client class
├── commands/     prefix/ and slash/ commands
├── events/       Discord event handlers
├── antinuke/     Antinuke protection modules
├── logging/      Server logging modules
├── modules/      AFK, autoreact, autoresponder, media
├── functions/    Welcome, autorole helpers
├── handlers/     Command, event, antinuke, logging loaders
├── tasks/        Giveaway checker, premium expiry
├── utils/        Logger, pagination, executor, etc.
└── config/       config.js, emojis.js
```

---

## 🎵 Music Setup (Lavalink)

Velyx uses [Riffy](https://github.com/riffy-team/riffy) + Lavalink for music.

### 1. Run a Lavalink server
Download from [lavalink.dev](https://lavalink.dev) or use a free public node.

### 2. Set env variables
```
LAVALINK_HOST=your_lavalink_host
LAVALINK_PORT=2333
LAVALINK_PASSWORD=youshallnotpass
LAVALINK_SECURE=false
```

### Music Commands
| Command | Description |
|---------|-------------|
| `/play` | Play a song (YouTube, Spotify, SoundCloud) |
| `/nowplaying` | Canvas card of current track + progress bar |
| `/queue` | Canvas card of the queue |
| `/skip` | Skip current track |
| `/stop` | Stop and leave VC |
| `/pause` | Pause playback |
| `/resume` | Resume playback |
| `/volume` | Set volume 0–100 |
| `/loop` | Set loop: off / track / queue |
| `/shuffle` | Shuffle the queue |
| `/seek` | Seek to position (e.g. `1:30`) |

---

## 😄 Fun Commands
| Command | Description |
|---------|-------------|
| `/gay` | Gay percentage meter |
| `/lesbian` | Lesbian energy meter |
| `/sigma` | Sigma grindset score |
| `/iq` | IQ test result |
| `/pp` | PP size measurement |
| `/horny` | Horny level meter |
| `/ship` | Ship compatibility % |
| `/roast` | Roast someone |
| `/8ball` | Ask the magic 8-ball |
| `/coinflip` | Flip a coin |
| `/dice` | Roll a dice |
| `/rps` | Rock Paper Scissors |


# By NotDarku_

#  क!तील
