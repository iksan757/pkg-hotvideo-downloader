# 🎬 Hot Video Downloader

A fast video downloader that extracts direct stream links with selectable quality and high-speed DNS support.

## 🚀 Features
- Supports resolutions from 240p to 1080p (Full HD).
- Cloudflare DNS (1.1.1.1) support for a more stable connection.
- Interactive mode (`-i`) and direct mode.
- Custom storage folder configuration.

## 📦 Installation

Run the following command:

```bash
pkg install ./hotvideo-downloader_1.0.0_all.deb
```

## 📖 Usage

```bash
# Download directly with default resolution (480p)
hotvideo "[https://example.com](https://example.com)"

# Download with 720p resolution and custom DNS
hotvideo "[https://example.com](https://example.com)" -r 720p -d

# Enter interactive mode
hotvideo -i
```

## 📜 License
Developed by **Iksan Ramadhan <rumasoreng757@gmail.com>**. Licensed under the [MIT License](LICENSE).
