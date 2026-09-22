<!-- ========================================================= -->
<!--                    DeeDevBot MD README                    -->
<!-- ========================================================= -->

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="38" width="100%" alt="divider" />
</p>

<h1 align="center">⚡ DeeDevBot MD ⚡</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=24&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=850&lines=Advanced+Multi-Device+WhatsApp+Bot;Automation+%7C+Moderation+%7C+Media+%7C+AI;Powerful+Group+Management+and+Owner+Controls;Built+for+Speed%2C+Control+and+Reliability" alt="DeeDevBot MD typing animation" />
</p>

<p align="center">
  <img src="./assets/bot_image.jpg" width="420" alt="DeeDevBot MD" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-Node.js-111111?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/WhatsApp-Multi--Device-111111?style=for-the-badge&logo=whatsapp&logoColor=25D366" alt="WhatsApp Multi Device" />
  <img src="https://img.shields.io/badge/Baileys-WhatsApp%20Web-111111?style=for-the-badge" alt="Baileys" />
  <img src="https://img.shields.io/badge/Commands-200%2B-111111?style=for-the-badge&logo=probot&logoColor=00D9FF" alt="200+ command triggers and aliases" />
</p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VbBV8Lq5q08UdpLG6J2F">
    <img src="https://img.shields.io/badge/📢_OFFICIAL_CHANNEL-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Official WhatsApp Channel" />
  </a>
  <a href="https://chat.whatsapp.com/GA4WrOFythU6g3BFVubYM7?mode=wwt">
    <img src="https://img.shields.io/badge/💬_SUPPORT_GROUP-0A66C2?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Support Group" />
  </a>
</p>

<p align="center">
  <b>DeeDevBot MD</b> is a modular WhatsApp automation bot built around a command-based architecture with group administration, moderation, media processing, download tools, AI utilities, owner controls, games, automation and advanced message handling.
</p>

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="38" width="100%" alt="divider" />
</p>

## ✨ Highlights

- ⚡ **Multi-device WhatsApp automation** powered through the Baileys ecosystem.
- 🧩 **Modular command architecture** with individual handlers inside `commands/`.
- 🎛️ **Public / private bot mode** with owner and sudo permission checks.
- 🛡️ **Group protection suite** including anti-link, anti-tag, anti-badword and anti-delete tools.
- 👑 **Advanced group administration** for promote, demote, kick, mute, ban, warnings, group settings and tagging.
- 🤖 **AI commands** including GPT/Gemini-style chat, image generation workflows and Sora integration.
- 🎵 **Media and downloader tools** for YouTube, TikTok, Instagram, Facebook, Spotify and more.
- 🖼️ **Image and sticker tools** including sticker conversion, crop, blur, background removal, enhancement and emoji mixing.
- 👁️ **View-once workflows** including standard view-once handling and custom owner-routed triggers.
- 📲 **Automation controls** for auto-status, auto-read, auto-typing, auto-reaction and blue-tick behavior.
- 🎮 **Games and entertainment** including Tic-Tac-Toe, Hangman, Trivia, Truth or Dare, jokes, quotes and social cards.
- 🧹 **Runtime housekeeping** with custom temporary storage handling and periodic cleanup for hosted environments.
- 📊 **Message activity utilities** including member message counting and top-member commands.
- 🔐 **Owner-focused controls** for sudo management, sessions, profile settings, updates and system cleanup.

---

## 🧠 What DeeDevBot MD Can Do

| Category | Included capabilities |
|---|---|
| **Core** | `.menu`, `.help`, `.ping`, `.alive`, `.owner`, `.settings`, `.mode` |
| **Group Admin** | `.promote`, `.demote`, `.kick`, `.mute`, `.unmute`, `.ban`, `.unban`, `.warn`, `.warnings`, `.tagall`, `.hidetag`, `.staff`, `.groupinfo` |
| **Group Settings** | `.setgdesc`, `.setgname`, `.setgpp`, `.resetlink`, `.welcome`, `.goodbye` |
| **Protection** | `.antilink`, `.antitag`, `.antibadword`, `.antidelete`, `.pmblocker`, `.anticall` |
| **Automation** | `.autostatus`, `.autoread`, `.autotyping`, `.areact`, `.autoreact`, `.bluetick`, `.showbluetick` |
| **View Once** | `.vv`, `.aaah`, `.eeeh`, `.iiih`, `.oooh`, `.uuuh` |
| **Stickers & Images** | `.sticker`, `.s`, `.simage`, `.crop`, `.blur`, `.removebg`, `.remini`, `.enhance`, `.upscale`, `.attp`, `.emojimix` |
| **Media Download** | `.play`, `.song`, `.mp3`, `.video`, `.ytmp4`, `.tiktok`, `.instagram`, `.ig`, `.igs`, `.facebook`, `.fb`, `.spotify` |
| **AI & Smart Tools** | `.gpt`, `.gemini`, `.imagine`, `.dalle`, `.flux`, `.sora`, `.translate`, `.weather`, `.news`, `.lyrics` |
| **Web & Utility** | `.tourl`, `.url`, `.ss`, `.ssweb`, `.screenshot`, `.tts`, `.github`, `.jid` |
| **Games** | `.ttt`, `.tictactoe`, `.move`, `.surrender`, `.hangman`, `.guess`, `.trivia`, `.answer`, `.8ball` |
| **Fun** | `.truth`, `.dare`, `.meme`, `.joke`, `.quote`, `.compliment`, `.insult`, `.flirt`, `.ship`, `.character`, `.waste` |
| **Anime / Reactions** | `.animu`, `.nom`, `.poke`, `.cry`, `.kiss`, `.pat`, `.hug`, `.wink`, `.facepalm`, `.loli` |
| **Text Effects** | `.metallic`, `.ice`, `.snow`, `.matrix`, `.neon`, `.thunder`, `.hacker`, `.blackpink`, `.glitch`, `.fire` and more |
| **Owner / System** | `.sudo`, `.clearsession`, `.cleartmp`, `.setpp`, `.update` |

> The table shows the main commands and aliases currently wired into the bot. DeeDevBot MD contains **200+ command triggers and aliases** across its full command router.

---

## 🏗️ Project Structure

```text
DeeDevBot-MD/
├── assets/          # Bot images and media assets
├── commands/        # Modular command handlers
├── data/            # Persistent JSON/config state
├── lib/             # Shared helpers and core utilities
├── scripts/         # Maintenance / support scripts
├── session/         # WhatsApp session data
├── .env             # Environment configuration
├── config.js        # Main configuration support
├── index.js         # Bot entry point
├── main.js          # Message router and command dispatcher
├── package.json     # Node.js dependencies and scripts
└── settings.js      # Bot identity and runtime settings
```

### Core flow

```text
WhatsApp Event
     │
     ▼
  index.js
     │
     ▼
  main.js
     │
     ├── Permission / mode checks
     ├── Moderation handlers
     ├── Automation handlers
     └── Command router
              │
              ▼
        commands/*.js
              │
              ▼
       WhatsApp response
```

---

## 🚀 Quick Start

### 1. Requirements

Make sure your environment has:

- **Node.js**
- **npm**
- A WhatsApp account for pairing/session authentication
- Internet access for commands that depend on external services

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the bot

Review and configure:

```text
settings.js
.env
config.js
```

For owner-routed features, ensure the owner number is configured correctly through the bot settings or environment configuration.

Example environment value:

```env
OWNER_NUMBER=255XXXXXXXXX
```

Use the international number format without `+` unless your local configuration explicitly expects otherwise.

### 4. Start DeeDevBot MD

```bash
node index.js
```

When the bot starts successfully, complete the required WhatsApp pairing/session process for your setup.

---

## ⚙️ Main Automation & Control Features

### 🟢 Auto Status
Control automated status handling from the bot using the existing auto-status command system.

### 🔵 Blue Tick Controls
DeeDevBot MD includes dedicated blue-tick/read-receipt command logic alongside auto-read behavior.

### ⌨️ Auto Typing
Typing-presence automation is integrated into normal messages and supported commands.

### ❤️ Auto Reaction
Reaction handling can be controlled through `.areact`, `.autoreact` and related command aliases.

### 🚫 PM Blocker
The bot can restrict non-owner private messages when the PM blocker is enabled.

### 📞 Anti Call
Owner-controlled anti-call functionality is available through `.anticall`.

### 🗑️ Anti Delete
Messages can be stored and handled through the anti-delete system when configured.

### 👁️ View-Once Handling
The bot includes normal `.vv` handling plus custom triggers:

```text
.aaah
.eeeh
.iiih
.oooh
.uuuh
```

The custom workflow is designed to route its processed result to the configured owner while keeping the source command flow silent.

---

## 🛡️ Group Moderation

DeeDevBot MD includes several layers of group control:

```text
Anti-Link      → Link protection and moderation
Anti-Tag       → Tag-related protection
Anti-Badword   → Bad-word filtering
Anti-Delete    → Deleted-message handling
Warnings       → Member warning management
Ban / Unban    → Bot-level user restrictions
Mute / Unmute  → Group messaging controls
Promote/Demote → Admin management
Kick           → Member removal
```

Administrative commands perform permission checks before sensitive group actions are executed.

---

## 🎨 Media & Creative Tools

DeeDevBot MD includes a large collection of creative and media commands:

- Sticker creation and sticker-to-image conversion
- Sticker crop support
- Image blur
- Background removal
- Image enhancement / upscale workflows
- Emoji mixing
- Telegram sticker utilities
- Text effects and themed image generators
- Screenshot / web screenshot tools
- Image generation commands
- Social-style cards and meme utilities

---

## 🎧 Download & Social Media Tools

Supported command workflows include:

```text
YouTube     → Play, audio and video commands
TikTok      → TikTok media handling
Instagram   → Posts / reels plus IGS workflows
Facebook    → Facebook media handling
Spotify     → Spotify command workflow
URL Tools   → Media-to-URL utilities
```

Availability can depend on the external service, endpoint or API used by the relevant command module.

---

## 🧹 Hosting Reliability

The main message system includes hosted-environment protections such as:

- Custom temporary directory handling
- Automatic temporary-file cleanup
- Reduced dependency on the host system `/tmp`
- Command-level error handling
- Public/private access mode checks
- Owner/sudo authorization
- Group-admin validation for sensitive actions

These features help keep the bot stable during long-running sessions and media-heavy workloads.

---

## 🔐 Security Before Publishing

If you are uploading DeeDevBot MD to a public GitHub repository, **never commit private credentials**.

Make sure these remain private:

```text
.env
session/
WhatsApp credentials / auth files
API keys
OWNER_NUMBER if you do not want it public
private JSON credentials
```

Recommended `.gitignore` coverage:

```gitignore
node_modules/
.env
session/
temp/
*.log
```

> Before your first `git push`, inspect the staged files with `git status` and confirm that no session credentials, tokens or private keys are included.

---

## 🧩 Adding a New Command

The project is structured so command logic can stay isolated inside `commands/`.

Typical pattern:

```text
1. Create commands/yourcommand.js
2. Export the command handler
3. Import it in main.js
4. Add its case to the main command router
5. Restart and test the bot
```

This keeps features modular and makes future maintenance easier.

---

## 💻 Development

For local development:

```bash
npm install
node index.js
```

When making changes:

1. Keep new command logic inside the appropriate module.
2. Avoid modifying unrelated features.
3. Test syntax before deployment.
4. Test owner/admin permission behavior separately.
5. Test both private and group message flows where relevant.

---

## 📣 Community

<p align="center">
  <a href="https://whatsapp.com/channel/0029VbBV8Lq5q08UdpLG6J2F">
    <img src="https://img.shields.io/badge/Follow-DeeDevBot_MD_Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="DeeDevBot MD Channel" />
  </a>
  <a href="https://chat.whatsapp.com/GA4WrOFythU6g3BFVubYM7?mode=wwt">
    <img src="https://img.shields.io/badge/Join-Support_Group-0A66C2?style=for-the-badge&logo=whatsapp&logoColor=white" alt="DeeDevBot MD Support" />
  </a>
</p>

---

## ⚠️ Disclaimer

DeeDevBot MD is an independent automation project and is **not affiliated with, endorsed by, or officially connected to WhatsApp or Meta**.

Use the bot responsibly, respect user privacy, comply with applicable laws and platform rules, and only deploy features in environments where you are authorized to operate them.

---

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="38" width="100%" alt="divider" />
</p>

<h3 align="center">⚡ DeeDevBot MD</h3>

<p align="center">
  <b>Automation • Moderation • Media • AI • Control</b><br/>
  Built as a modular WhatsApp bot for powerful everyday automation.
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=25D366&center=true&vCenter=true&width=700&lines=Fast.+Modular.+Feature-Rich.;DeeDevBot+MD+%E2%9A%A1" alt="Footer typing animation" />
</p>

<p align="center">
  <img src="https://i.imgur.com/dBaSKWF.gif" height="38" width="100%" alt="divider" />
</p>
