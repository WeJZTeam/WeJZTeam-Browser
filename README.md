# WeJZTeam Browser (coming soon)
A high-performance, modern web browser engineered for speed, privacy, and a premium user experience. Built with the latest web technologies to provide a sleek, efficient, and customizable browsing environment.
## 🚀 Key Features in Detail
### 🛡️ Built-in Ad & Tracker Blocker
- **Comprehensive Blocking**: Blocks 79+ domains known for ads, trackers, and intrusive scripts.
- **Privacy Protection**: Blocks Google Analytics, Facebook Pixels, Hotjar, and many other tracking services.
- **Performance Boost**: By blocking heavy ad scripts, pages load significantly faster.
- **Always Active**: Enabled by default to protect your privacy from the first second.
### 📦 Chrome Extension Support (CRX)
- **Direct CRX Downloads**: Download extensions directly from the Chrome Web Store.
- **Smart Parsing**: Automatically extracts extension IDs from store URLs.
- **Automated Extraction**: Downloads, extracts, and prepares extensions for loading in the browser.
- **Multiple Fail-safes**: Uses multiple download methods including Google's update services and `curl` fallback.
### 📂 Advanced Tab Management
- **Multi-Tab Architecture**: Scalable system for handling multiple tabs simultaneously without lag.
- **Intelligent Switching**: Seamless transitions between active views.
- **Lifecycle Control**: Tabs are created, managed, and destroyed carefully to save system resources.
- **Shortcut Support**: Supports middle-click and Ctrl+click to open links in new background tabs.
### 🔖 Bookmark & History Management
- **One-Click Bookmarking**: Easy star icon in the toolbar to save your favorite sites.
- **Persistent Storage**: All bookmarks are saved in a local `bookmarks.json` file.
- **Rich Metadata**: Saves site titles, URLs, and favicons for easy identification.
- **Automated Checks**: Automatically detects if the current page is already bookmarked.
### 🔍 Smart Address Bar (Omnibox)
- **Automatic Routing**: Detects if input is a URL or a search query.
- **Engine Choice**: Choose between **Google**, **DuckDuckGo**, or **Bing** as your primary search engine.
- **Secure Indicators**: Clear visual 🔒 icon for HTTPS/SSL secured websites.
- **Smart Suggestions**: Intuitive interface for quick navigation.
### 🎨 Premium UI & Customization
- **Modern Aesthetics**: Built with **Tailwind CSS v4** and Lucide Icons for a state-of-the-art look.
- **Glassmorphism**: Beautiful translucent effects throughout the shell.
- **Custom Titlebar**: Integrated window controls that match the browser's theme.
- **Internal Pages**: Custom `wezj://newtab` and `wezj://settings` routes for a unified experience.
## 🛠 Advanced Tech Stack
- **Framework**: React 18+ with TypeScript.
- **Engine**: Electron for reliable desktop performance.
- **Build Tool**: Vite for lightning-fast development and optimized bundles.
- **Styling**: Tailwind CSS v4 (the latest standard in CSS).
- **Icons**: Lucide React for consistent, high-quality iconography.
- **State**: Zustand for lightweight and fast state management.
## 📥 Installation & Setup
Quick download and installation steps
### For Linux
  
1. `wget https://raw.githubusercontent.com/WeJZTeam/JZFileBrowser/main/WeJZTeam Browser-Linux-0.0.0.deb`
2. `chmod +x "WeJZTeam Browser-Linux-0.0.0.deb"`
3. `sudo dpkg -i "WeJZTeam Browser-Linux-0.0.0.deb"`

### For Windows

1. `curl -L "https://raw.githubusercontent.com/WeJZTeam/JZFileBrowser/main/WeJZTeamBrowser-win.exe" -o "WeJZTeamBrowser-win.exe"`
2. `WeJZTeamBrowser-win.exe`

## 🔄 Updating & Maintenance
- **To Update**: Simply replace your current version with the latest download from the Releases page. Your settings and bookmarks will be preserved in your home directory (`~/.config/wejzteam-browser`).
- **To Uninstall (Portable)**: Delete the `.AppImage` file and the config folder: `rm -rf ~/.config/wejzteam-browser`.
- **To Uninstall (Debian)**: Run `sudo apt remove wejzteam-browser`.
---
**Developed with ❤️ by [WeJZTeam](https://github.com/WeJZTeam/)**  
*Engineered for Performance. Crafted for Privacy.*
