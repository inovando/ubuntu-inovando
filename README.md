# ubuntu-inovando
Custom Ubuntu Desktop bash script with pre-installed/configured apps for a modern web development environment

![terminal after success](terminal-success.png)

## Setup
```bash
wget https://raw.githubusercontent.com/inovando/ubuntu-inovando/master/setup.sh
chmod +x setup.sh
bash setup.sh
# after this command, reboot your system :)
```

## Features
- [x] Git
- [x] Curl
- [x] ssh-keygen
- [x] VSCode
- [x] Chrome
- [x] openFortiGUI
- [x] Postman
- [x] Discord
- [x] Spotify
- [x] DBeaver CE
- [x] Docker
- [x] Docker Compose
- [x] Postgres (from docker image)
- [x] NVM
- [x] Yarn
- [x] ZSH
- [x] Flameshot (print part of screen and copy to clipboard)
- [x] Peek (record GIFs)
- [x] Android Studio

## FAQ

### What's the Postgres password?
- root

### I already have Node.js/npm/docker/etc installed, will it update for me?
- No, this script will only install apps if you didn't have them installed before (to prevent duplications).
