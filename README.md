# 🚀 ASTRAL-AI Launcher

AI-powered Minecraft mod launcher with visual management and conflict detection.

## ✨ Features

- 🎯 **Visual Mod Board** - Drag & drop interface for mod management
- 🤖 **AI-Powered Analysis** - Smart conflict detection and resolution
- 🔐 **OAuth Authentication** - Secure login with ASTRAL-AI account
- 📱 **Modern UI** - Beautiful, responsive interface with cosmic theme
- ⚡ **Fast Performance** - Built with Rust + Tauri for speed
- 🔧 **Nitrolaunch Integration** - Advanced Minecraft launching capabilities

## 📥 Download

Get the latest version from the [Releases](https://github.com/TheVirusNVGM/astral-ai-launcher/releases) page.

## 🛠️ Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v20+)
- [Rust](https://rustup.rs/) (latest stable)
- Windows 10/11 (currently Windows-only)

### Setup

```bash
# Clone the repository
git clone https://github.com/TheVirusNVGM/astral-ai-launcher.git
cd astral-ai-launcher

# Install dependencies
npm install

# Run in development mode
npm run tauri:dev
```

### Build

```bash
# Build for production
npm run tauri:build
```

## 🏗️ Architecture

- **Frontend**: React + TypeScript + Vite
- **Backend**: Rust + Tauri
- **Authentication**: OAuth 2.0 with ASTRAL-AI website
- **Launcher Core**: Nitrolaunch (Minecraft launching library)

## 📂 Project Structure

```
src/                 # React frontend
├── components/      # UI components  
├── services/        # API services
├── pages/          # Application pages
└── i18n/           # Internationalization

src-tauri/          # Rust backend
├── src/            # Tauri application code
├── nitrolaunch/    # Minecraft launcher library
└── icons/          # Application icons

.github/workflows/  # CI/CD pipelines
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- [Tauri](https://tauri.app/) for the amazing desktop app framework
- [Nitrolaunch](https://github.com/Nickthegamer24/nitrolaunch) for Minecraft launching capabilities
- React and Rust communities for excellent tooling

---

Made with ❤️ by [TheVirusNVGM](https://github.com/TheVirusNVGM)
