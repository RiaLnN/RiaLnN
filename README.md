# Hi, I'm RiaLnN 👋

I’m a developer passionate about turning ideas into real, working products. I love building web apps, Telegram bots, and automation tools that people actually use.

---

## 🛠 Skills & Tech Stack

- Languages: Python (FastAPI, aiogram), JavaScript (Vanilla JS), TypeScript, SQL (PostgreSQL, SQLite)
- Backend: FastAPI, REST APIs, microservices, Alembic migrations
- Frontend: Vanilla JS/TS, HTML, CSS, responsive UI/UX
- Databases: PostgreSQL, SQLite
- Tools & DevOps: Docker, Docker Compose, Git, CI/CD, Azure, Heroku, Cloudflare, VS Code
- Additional: Telegram bots, automation, OCR, async processing, PyPI packaging, localization, data analytics

---

## 🌟 Projects

### 1. osu-finder

Asynchronous CLI tool for discovering osu! beatmaps using local difficulty and performance analysis instead of relying only on API metadata.

- Downloads lightweight `.osu` files and calculates star rating, PP, and playstyle locally with `rosu-pp-py`
- Evaluates multiple mod combinations (NM, DT, HDHR, etc.) per beatmap
- Auto-generates search presets from a player's top plays
- Advanced filtering by PP, star rating, BPM, length, AR, CS, OD
- Skips already-installed maps via a local cache, plus a configurable blacklist
- Published on PyPI, installable via `pipx install osu-finder`
- 🔗 [Repository](https://github.com/RiaLnN/osu-finder) · 📦 [PyPI package](https://pypi.org/project/osu-finder/)

### 2. Dota 2 Replay Cut

Automation toolkit for downloading Dota 2 replays, launching them in-game, and saving highlight clips through OBS Replay Buffer.

- Replay discovery and download via the OpenDota API
- Automatic replay launch in Dota 2 through Steam
- OBS WebSocket integration for replay buffer control and clip saving
- OCR-based kill detection (KDA) and timeline correction (in-game clock)
- Two workflows: continuous "Full Watch" and targeted "Timeline Jumps"
- Multi-match queue runner for batch processing
- 🔗 [Repository](https://github.com/RiaLnN/dota2_replay_cut)

### 3. TikTok Trend Music Bot

Telegram bot that finds trending TikTok music tracks and delivers them as playable audio with source video previews.

- Trend search with flexible filters: keywords, region, time period, sort mode
- Sends tracks as Telegram audio messages along with source video context
- Paid subscription flow via Telegram Stars, with admin subscription management
- Persists user search settings and subscription state
- Deployed on Heroku
- 🔗 [Repository](https://github.com/RiaLnN/tiktok-trend-music) · 🤖 Bot: [t.me/toktrends_bot](https://t.me/toktrends_bot)

### 4. TelegramBot Whisper

Telegram bot for voice transcription and AI-powered text processing.

- Speech-to-text via Groq Whisper (`whisper-large-v3`)
- Message summarization and AI reply generation via a LLaMA-compatible API
- Async task processing with Celery + Redis
- Per-chat settings (transcription mode, AI tone preset) stored in PostgreSQL
- ⚠️ Currently inactive / intermittent — hosted on an Azure student subscription that can't reliably handle the load
- 🔗 [Repository](https://github.com/RiaLnN/telegramBot_whisper)

### 5. Utilities & Automation Scripts

- Python scripts for data parsing, task automation, and workflow optimization
- Integrations with APIs and custom tools for personal or small business use

---

## 🔗 Contact & Freelance

- Telegram: [t.me/rialnns](https://t.me/rialnns)
- Email: [max07070799@gmail.com](mailto:max07070799@gmail.com)
- Open for freelance: web apps, Telegram bots, automation, integrations

---

## 💡 About Me

I thrive on bringing ideas to life through code. I constantly learn new technologies and enjoy building *intuitive, practical solutions* that people actually use.
