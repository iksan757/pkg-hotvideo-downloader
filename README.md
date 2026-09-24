# 🎬 Hot Video Downloader (v1.0.0)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Windows-blue)](https://github.com/iksan757/pkg-hotvideo-downloader)
[![Shell](https://img.shields.io/badge/Language-Bash-green)](https://www.gnu.org/software/bash/)

* Fast video downloader that extracts direct stream links with custom quality and high-speed DNS.

## 🚀 Features

- 📐 **Multiple Resolutions:** Supports video stream extraction ranging from `240p` to `1080p` (Full HD).
- ⚡ **High-Speed DNS:** Integrated Cloudflare DNS (`1.1.1.1`) support for a stable downloading process.
- 🎛️ **Dual Usage Modes:** Supports both direct command-line arguments and an interactive terminal menu (`-i`).
- 📁 **Custom Storage:** Configure download save paths directly via arguments.
- 📦 **Automatic Dependency Handling:** Runs seamlessly with `yt-dlp`, `aria2`, `python`, `ffmpeg`, and `bash`. ## 📥 Installation

---
## 📥  Installation

📱 1. Termux
```
git clone
https://github.com/iksan757/pkg-hotvideo-downloader.git && cd  pkg-hotvideo-downloader && pkg update && pkg install -y ./hotvideo-downloader_1.0.0_all.deb && hotvideo -u
```
🐧 2. Debian / Ubuntu / Kali Linux / Mint
```bash
git clone
https://github.com/iksan757/pkg-hotvideo-downloader.git  && sudo apt update && sudo apt install -y ./hotvideo-downloader_1.0.0_all.deb
```
🏹 3. Arch Linux / Manjaro
```bash
sudo pacman -S --needed --noconfirm git python python-yt-dlp aria2 ffmpeg && git clone
https://github.com/iksan757/pkg-hotvideo-downloader.git && sudo cp pkg-hotvideo-downloader/bin/* /usr/local/bin/ && sudo chmod +x /usr/local/bin/*
```
---

##📖 Usage

Once installation is complete, you can immediately run the `hotvideo` command:
```
Direct download (Default resolution 480p)
  hotvideo "[https://example.com/video](https://example.com/video)"

Custom resolution option (240p / 360p / 480p / 720p / 1080p)
  hotvideo "[https://example.com/video](https://example.com/video)" -r 720p

Use fast Cloudflare DNS connection (1.1.1.1)
   hotvideo "[https://example.com/video](https://example.com/video)" -r 1080p -d
Interactive mode (Terminal menu)
   hotvideo -i
```
---

##🛠️ Full Command Options

| Flag / Opsi | Keterangan | Contoh |
| --- | --- | --- |
| **URL** | Tautan video yang ingin di-download | `hotvideo "https://..."` |
| **-r, --resolution** | Pilih kualitas video (240p, 360p, 480p, 720p, 1080p) | `hotvideo -r 720p` |
| **-d, --dns** | Aktifkan Cloudflare DNS (1.1.1.1) | `hotvideo -d` |
| **-i, --interactive** | Buka menu tampilan interaktif | `hotvideo -i` |
| **-h, --help** | Tampilkan menu bantuan | `hotvideo -h` |

---

##⚙️ Key Dependencies
This application requires the following tools (automatically installed via the installation methods above):

- [Python](https://www.python.org/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [yt-dlp-ejs](https://github.com/yt-dlp/ejs)
- [aria2](https://aria2.github.io)
- [ffmpeg](https://ffmpeg.org)

---

## For Support
*  Treat me to coffee ☕: [Treat](https://saweria.co/tuanmuda7)
*  Instagram: *@ikhsan_11rs*

---

📄 License
Distributed under the MIT License. See LICENSE for more information.
