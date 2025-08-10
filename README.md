# 🌙 LunaIPTV

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![PyQt6](https://img.shields.io/badge/GUI-PyQt6-green)](https://pypi.org/project/PyQt6/)
[![VLC](https://img.shields.io/badge/Playback-VLC-orange)](https://www.videolan.org/vlc/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)
[![Made With Love](https://img.shields.io/badge/Made%20With-%E2%9D%A4-red)](#)

A modern, user-friendly IPTV player built with **Python** & **PyQt6** — lightweight, customizable, and designed to make streaming effortless.  

![LunaIPTV Logo](assets/logo.png) <!-- optional if you have a logo -->

---

## 📖 Description
LunaIPTV is a sleek IPTV client built for smooth, reliable streaming.  
It integrates **Xstream API login**, **VLC playback**, and a clean **PyQt6 interface** to give you a no-fuss IPTV experience.  
Whether it’s live TV, sports, or on-demand series, LunaIPTV keeps it simple without sacrificing power.

---

## ✨ Features

### 🎯 Core
- **Xstream API Login** – quick, secure authentication with your IPTV provider.
- **Channel & EPG Browsing** – see what's on now and what's coming up.
- **VLC Integration** – full codec support for smooth, lag-free playback.
- **Search & Filter** – quickly find your favorite channels.

### 🖥 User Interface
- **Clean, Modern PyQt6 Design** – responsive layout for desktops.
- **Category Tabs** – Live TV, Movies, Series — switch in a click.
- **Toolbar Controls** – Settings, About, Refresh at your fingertips.
- **Custom App Icon** – LunaIPTV branding in the window and taskbar.

### 📺 Playback
- **Supports HD, Full HD, and 4K** – based on your provider’s stream quality.
- **Buffer Management** – smoother playback, fewer interruptions.
- **Full-Screen Mode** – immersive viewing without distractions.

### ⚙ Extras
- **Automatic VLC Path Detection** – guides first-time setup.
- **Minimal Error Popups** – avoids random timeout spam.
- **Portable Build Option** – distribute as a single EXE (PyInstaller).

---

## 📸 Screenshots

> *(Replace placeholders with actual images. Consider blurring personal IPTV info.)*

| Live TV View | Category Browsing | Settings |
|--------------|-------------------|----------|
| ![Screenshot 1](assets/screenshot1.png) | ![Screenshot 2](assets/screenshot2.png) | ![Screenshot 3](assets/screenshot3.png) |

---

## 🚀 Installation

### From Source
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/LunaIPTV.git
cd LunaIPTV

# Install dependencies
pip install -r requirements.txt

# Run
python LunaIPTV.py
