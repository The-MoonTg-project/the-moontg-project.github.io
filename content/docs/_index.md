---
title: Documentation
next: /docs/installation/
---

Welcome to the Moon Userbot documentation!

## Getting Started

{{% steps %}}

### Step 1: Prerequisites

Before installing Moon Userbot, you'll need:
- A Telegram account (not recently registered)
- Telegram API credentials from [my.telegram.org](https://my.telegram.org/)
- A method of deployment (Cloud, Docker, or Local)

### Step 2: Get Your API Credentials

1. Visit [my.telegram.org](https://my.telegram.org/)
2. Log in with your Telegram account
3. Click "API Development Tools"
4. Create a new application
5. Note down your `API_ID` and `API_HASH`

### Step 3: Generate a Session String

{{< callout type="info" >}}
  You can skip this step if you wish to run/deploy the userbot locally.
{{< /callout >}}

Moon Userbot requires a Pyrogram session string for authentication. You can generate one:
- [Use the generation script](https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/string_gen.py)
- [Run on Replit](https://replit.com/@ABHITHEMODDER/MoonUb-Session-Gen)

### Step 4: Choose Your Deployment Method

{{< cards >}}
  {{< card link="/docs/installation/cloud" title="Cloud Deploy" icon="cloud" subtitle="Deploy on Koyeb, Render, or Heroku" >}}
  {{< card link="/docs/installation/docker" title="Docker" icon="cube" subtitle="Containerized deployment" >}}
  {{< card link="/docs/installation/local" title="Local Host" icon="terminal" subtitle="Run on your own machine" >}}
{{< /cards >}}

### Step 5: Configure Environment Variables

Set up the required environment variables based on your deployment method. See the [Environment Variables](/docs/installation#environment-variables) section for details.

### Step 6: Enjoy!

Your Moon Userbot is now ready to use.

{{% /steps %}}

## Need Help?

- 📢 [Support Channel](https://t.me/moonuserbot)
- 💬 [Community Chat](https://t.me/moonub_chat)
- 🐛 [Report Issues](https://github.com/The-MoonTg-project/Moon-Userbot/issues)
