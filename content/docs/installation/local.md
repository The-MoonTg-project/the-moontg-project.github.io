---
title: Local Host
weight: 3
---

## Linux (WSL compatible)

### Install Git

There are instructions for installing on several different Unix distributions on the Git website, at <https://git-scm.com/download/linux>

### Clone the repo

```shell {filename="SHELL"}
git clone https://github.com/The-MoonTg-project/Moon-Userbot.git
```

### Installation

```shell {filename="SHELL"}
cd Moon-Userbot
chmod +x install.sh
./install.sh
```

**Installer tested on:**
- Arch
- Debian
- Ubuntu
- WSL (APT based distros)

Feel free to test on other distros and let us know!

## Termux (Android)

1. Download and install Termux from F-Droid or GitHub

2. Copy this command and paste in Termux:

2. Copy this command and paste in Termux:

```shell {filename="SHELL"}
curl -L# https://raw.githubusercontent.com/The-MoonTg-project/Moon-Userbot/master/termux-install.sh -o t-moonub.sh && bash t-moonub.sh
```

3. Termux may ask permission to work in the background, you should allow it.

10. Switch to Telegram and enjoy!

## Windows (WSL)

1. You need WSL feature enabled and install any WSL distro of your choice.

2. Follow the steps mentioned in the [Linux](#linux-wsl-compatible) section.

For additional WSL documentation, refer to Microsoft's WSL documentation.
