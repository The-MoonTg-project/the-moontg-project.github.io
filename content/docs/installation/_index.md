---
title: Installation
weight: 1
next: /docs/installation/cloud/
---

> [!CAUTION]
> **Don't install the userbot on recently registered accounts**

## Environment Variables

| Variable | Importance | Description | Source / Link | Default value |
| --- | --- | --- | --- | --- |
| `API_ID` | **Required** | Your Telegram API ID. | [my.telegram.org](https://my.telegram.org/) | `2040` |
| `API_HASH` | **Required** | Your Telegram API Hash. | [my.telegram.org](https://my.telegram.org/) | `b18441a1ff607e10a989891a5462e627` |
| `STRINGSESSION` | **Required*** | Pyrogram session string. *Necessary for Docker/Cloud.* | [Use Script](https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/string_gen.py) OR [![Run on Repl.it](https://replit.com/badge)](https://replit.com/@ABHITHEMODDER/MoonUb-Session-Gen) | — |
| `DATABASE_TYPE` | **Required** | Set to `sqlite3` or `mongodb`. | — | — |
| `DATABASE_NAME` | **Required** | File name for sqlite3 (e.g., `db.sqlite3`) or Mongo DB name. | — | — |
| `DATABASE_URL` | **Optional** | Your MongoDB connection URL (only if using Mongo). | [MongoDB Atlas](https://www.mongodb.com/) | — |
| `PM_LIMIT` | **Optional** | Number of warnings before Anti-PM kicks in. | — | `4` |
| `MODULES_REPO_BRANCH` | **Optional** | Default custom modules repo branch | - | `main` |
| `SECOND_SESSION` | **Optional** | Session string for the Music Bot feature. | — | — |
| `GEMINI_KEY` | **Plugin** | API Key for Gemini AI features. | [Google AI Studio](https://makersuite.google.com/app/apikey) | — |
| `APIFLASH_KEY` | **Plugin** | API Key for taking web screenshots. | [ApiFlash](https://apiflash.com/dashboard/access_keys) | — |
| `RMBG_KEY` | **Plugin** | API Key for the `removebg` background remover. | [remove.bg](https://www.remove.bg/dashboard#api-key) | — |
| `VT_KEY` | **Plugin** | API Key for the [VirusTotal](https://www.virustotal.com/gui/) file scanner. | [VirusTotal](https://www.virustotal.com/gui/) | — |
| `COHERE_KEY` | **Plugin** | API Key for Cohere AI features. | [Cohere Dashboard](https://dashboard.cohere.com/api-keys) | — |

### Quick Notes

- **Database:** If you are using `sqlite3`, you can leave `DATABASE_URL` blank.
- **Sessions:** If `STRINGSESSION` is not provided, the bot will attempt to generate one at startup via the terminal, but this is not recommended for headless environments like Heroku or Docker.
