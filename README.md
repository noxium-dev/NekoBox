<div align="center">

# 🐱 NekoBox

### Modern Bulk Image Downloader for Image Boards & Galleries

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Electron](https://img.shields.io/badge/Electron-28.0-47848f?logo=electron)
![React](https://img.shields.io/badge/React-18.2-61dafb?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178c6?logo=typescript)

---

**A high-performance desktop application for bulk downloading images and galleries from popular image boards and art platforms. Built with Electron, React, TypeScript, and Python.**

[![⭐ Star this repository](https://img.shields.io/badge/⭐-Star_this_repository-yellow?style=for-the-badge)](https://github.com/noxium-dev/NekoBox)

[Features](#-features) • [Screenshots](#-screenshots) • [Supported Sites](#-supported-sites) • [Installation](#-installation) • [Quick Start](QUICKSTART.md) • [License](LICENSE)

</div>

---

## 📸 Screenshots

<div align="center">

### Main Interface
![NekoBox Interface](screenshots/Screenshot%202026-02-09%20140613.png)

### Download Queue
![Download Queue](screenshots/Screenshot%202026-02-09%20140711.png)

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### ⚡ High-Speed Downloads
- **5-50 concurrent downloads**
- Individual file progress tracking
- Real-time speed monitoring
- MB/s display for each file

</td>
<td width="50%">

### 🎯 Intelligent Download Modes
- **Single Mode**: Direct image/post URLs
- **Batch Mode**: Entire galleries & profiles
- Configurable download limits
- Smart queue management

</td>
</tr>
<tr>
<td width="50%">

### 🎨 Modern Interface
- Dark-themed UI built with Chakra UI
- Real-time progress visualization
- Expandable download cards
- Responsive design

</td>
<td width="50%">

### ⚙️ Flexible Configuration
- Custom download directories
- Quality settings
- File type filtering
- Naming pattern customization

</td>
</tr>
</table>

---

## 🌐 Supported Sites

### 🚀 Native High-Performance Scrapers
Built-in, optimized scrapers for:
- **Pixiv** (User galleries, bookmarks, rankings, tags)
- **Rule34** (Tag search, pools, posts)

### 🔌 Extensible Support (1000+ Sites)
Integration with **gallery-dl** enables support for thousands of additional sites including Reddit, DeviantArt, Danbooru, Gelbooru, and [many more](SUPPORTED_SITES.md).

> ⚠️ **Note**: Some sites may not work due to authentication restrictions or API changes. We are actively working to bring you more options and improve compatibility.

📋 See the full [**Supported Sites List**](SUPPORTED_SITES.md) for details.

---

## 📥 Installation

> **Platform**: Windows only (x64)

### Download the App

1. Download the latest release from the [Releases](../../releases) page
2. Run the installer (`NekoBox Setup.exe`)
3. Launch the application

### Install Gallery-dl (Optional but Recommended)

Gallery-dl is an **optional external extension** that provides support for 1000+ sites.

**Quick Install:**
```bash
pip install gallery-dl
```

📚 **See [GALLERY-DL-SETUP.md](GALLERY-DL-SETUP.md) for detailed installation instructions.**

### Why is Gallery-dl Optional?

Gallery-dl is licensed under **GPL-2.0+** (GNU General Public License). To maintain licensing flexibility and comply with GPL requirements, gallery-dl is kept as an optional external dependency that users install separately.

**Benefits:**
- ✅ Clear license boundaries
- ✅ Users choose whether to install it
- ✅ Always get the latest gallery-dl version
- ✅ Respects GPL-2.0+ licensing requirements

---

## 🚀 Getting Started

### Quick Start

Ready to start downloading? Check out our [**Quick Start Guide**](QUICKSTART.md) for:
- 📁 Setting up download folders
- 🎯 Using Single & Batch modes
- 🔐 Configuring authentication
- 🛠️ Troubleshooting common issues

---

## 🛠️ Technologies

<div align="center">

| Frontend | Backend | Tools |
|:--------:|:-------:|:-----:|
| **Electron** | **Python** | **Gallery-dl** |
| Desktop Framework | Scraping Engine | External Engine |
| **React** | **C++** | |
| UI Framework | Download Engine | |
| **TypeScript** | | |
| Type Safety | | |
| **Chakra UI** | | |
| Components | | |
| **Zustand** | | |
| State Management | | |

</div>

---

## 🚧 Roadmap

We are constantly working to improve NekoBox and bring you more features:

- [ ] 🌍 Multi-language support
- [ ] 🔔 Download completion notifications
- [ ] 📊 Advanced filtering and sorting
- [ ] 🎨 Custom theme support
- [ ] 🔄 Auto-update functionality
- [ ] 📱 Mobile companion app (future)

**Stay tuned for updates!** ⭐ Star this repo to follow our progress.

---

## ⚠️ Important Notes

### Authentication Requirements
- **Pixiv** requires login (cookie export)
- Some **gallery-dl** sites may require authentication
- Export cookies using browser extensions (e.g., "Get cookies.txt")
- Import cookies via Settings → Authentication

### Site Compatibility
- Some sites may experience temporary issues due to:
  - API changes or updates
  - Anti-bot measures
  - Rate limiting
  - Regional restrictions
- We actively monitor and update scrapers

### Performance Tips
- **Concurrent downloads**: Start with 10-20, adjust based on your connection
- **Authentication**: Pre-configure cookies for faster access
- **Disk space**: Ensure adequate space for batch downloads

---

## 📄 License

**Copyright © 2026. All Rights Reserved.**

This project is for **demonstration and portfolio purposes only**. See the [LICENSE](LICENSE) file for full terms.

> **Note**: This application uses gallery-dl as an optional external dependency. Gallery-dl is licensed under GPL-2.0+ and is not bundled with this application.

---

## 🙏 Credits

- **Gallery-dl**: [mikf/gallery-dl](https://github.com/mikf/gallery-dl) - GPL-2.0+
- Built with ❤️ using Electron, React, and TypeScript

---

## 💬 Support & Contributing

### Get Help
- 📖 Read the [Quick Start Guide](QUICKSTART.md)
- 🌐 Check [Supported Sites](SUPPORTED_SITES.md)
- 💬 Open an issue for bugs or questions

### Show Your Support
If you find NekoBox useful, please:
- ⭐ **Star this repository**
- 🐛 Report bugs and issues
- 💡 Suggest new features
- 📢 Share with others

---

<div align="center">

**⚠️ Disclaimer**

This tool is for personal use only. Please respect the terms of service of the websites you download from and respect copyright laws.

---

**Made with ❤️ for the community**

[![⭐ Star on GitHub](https://img.shields.io/github/stars/noxium-dev/NekoBox?style=social)](https://github.com/noxium-dev/NekoBox)

</div>
