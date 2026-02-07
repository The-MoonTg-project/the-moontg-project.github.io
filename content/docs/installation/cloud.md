---
title: Cloud Host
weight: 1
---

| Koyeb | Heroku | Render |
|-------|--------|--------|
| [![Deploy To Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/The-MoonTg-project/Moon-Userbot&branch=main&name=moonub) | [![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/The-MoonTg-project/moonub-cloud) | [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/The-MoonTg-project/Moon-Userbot) |

## Koyeb (Free)

[![Deploy To Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/The-MoonTg-project/Moon-Userbot&branch=main&name=moonub)

- **YT Video**:
{{< youtube 2m_yB7EllYc >}}
- **YT Video by a user**:
{{< youtube AmlFBZ26tY4 >}}


For most people above videos are enough to deploy Moon-Userbot.
Though if you still haven't been able to understand or deploy Moon-Userbot or maybe you're a reading type person (like me), then continue reading.

### 1. Create your account

Go to [Koyeb](https://www.koyeb.com/) and sign up. Remember to use your real Gmail or your GitHub for it.

### 2. Generate a string session

Using [this script](https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/string_gen.py) or [Replit](https://replit.com/@ABHITHEMODDER/MoonUb-Session-Gen).

### 3. Deploy

Click on [Deploy to Koyeb](https://app.koyeb.com/deploy?type=git&repository=github.com/The-MoonTg-project/Moon-Userbot&branch=main&name=moonub).

You'll be redirected to Koyeb's Deploy page.
It'll look like this:
| PC | Mobile |
|----|--------|
| ![Koyeb Deploy](https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/pcpreview.png) | ![Koyeb Deploy](https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/mobilepreview.png) |

### 4. Configure environment variables:

<table>
  <tr>
    <td>
      <b>Step A:</b> Click on <b>Environment Variables</b>
      <br><br>
      <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/envimg.png" width="600">
    </td>
  </tr>
  <tr>
    <td>
      <b>Step B:</b> Choose <b>Raw Editor</b>
      <br><br>
      <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/rawimg.png" width="600">
    </td>
  </tr>
  <tr>
    <td>
      <b>Step C:</b> Copy and paste <a href="https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/.env.dist">.env.dist</a>
      <br><br>
      <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/pasteedit.png" width="600">
    </td>
  </tr>
  <tr>
    <td>
      <b>Step D:</b> Edit the variables with your own values. <i>Do not remove any variable. Leave it blank if you don't want to use an optional variable.</i>
      <br><br>
      <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/variablesimg.png" width="600">
    </td>
  </tr>
  <tr>
    <td>
      <b>Step E:</b> Add a variable <code>PORT</code> with value <code>8080</code>
      <br><br>
      <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/portimg.png" width="600">
    </td>
  </tr>
</table>

### 5. Choose builder:

<p align="left">
  <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/builderimg.png" width="600">
</p>

* **Dockerfile**: Override Dockerfile location
    <br>
    <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/dockerimg.png" width="300">
    <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/overidedockerimg.png" width="300">

* **Buildpacks**: Override run command as <code>python main.py</code>
    <br>
    <img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/runcommandimg.png" width="600">

### 6. Choose region as Washington DC.
<img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/regionimg.png" width="600">

### 7. Change Exposed Port to 8080.
<img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/exposedportimg.png" width="600">

### 8. Click Deploy and wait for the build to finish.
<img src="https://raw.githubusercontent.com/wiki/The-MoonTg-project/Moon-Userbot/images/koyeb/finishimg.png" width="600">

## Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/The-MoonTg-project/Moon-Userbot)

1. Click on **[Deploy to Render](https://render.com/deploy?repo=https://github.com/The-MoonTg-project/Moon-Userbot)**.

2. Add your environment variables. Click **New Environment Variable**.

3. Copy and paste the contents of [.env.dist](https://github.com/The-MoonTg-project/Moon-Userbot/blob/main/.env.dist).

4. Edit the variables with your own values.

5. Click **Add** to save them.

6. Render will automatically build and deploy your Moon-Userbot.

## Heroku

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/The-MoonTg-project/moonub-cloud)

Heroku is no longer free. But you can still deploy Moon-Userbot on Heroku if you're a paid user of it. Since we don't have any paid Heroku account, we can't provide you with a detailed guide. Feel free to contribute if you have a paid Heroku account and can help us with the guide.
