# 🚀 ASTRAL-AI Launcher

## Why ASTRAL-AI Launcher?

### 🎯 Visual Mod Board

Transform mod management from a chore into a visual experience. Our drag-and-drop board interface lets you organize mods intuitively, categorize them visually, and see your entire modpack at a glance. No more digging through folders or guessing what mods conflict.

<div align="center">

![Visual Mod Board](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/4.png)

</div>

### 🤖 AI-Powered Modpack Builder

Simply describe what you want, and our AI creates a complete modpack for you. Using advanced RAG (Retrieval-Augmented Generation) architecture with semantic search across 50,000+ mods, the AI understands context, resolves dependencies automatically, and suggests compatible mods that match your vision.

**Example prompts:**
- *"Create a medieval fantasy modpack with magic and castles"*
- *"Build a tech-focused pack optimized for low-end PCs"*
- *"Make a vanilla+ experience with quality-of-life improvements"*

<div align="center">

![AI Panel](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/5.png)

</div>

### 🏥 Crash Doctor

Tired of cryptic crash logs? Crash Doctor analyzes your game crashes using AI, identifies root causes, and suggests precise fixes. It can automatically remove conflicting mods, update outdated versions, or recommend compatibility patches—saving hours of manual debugging.

<div align="center">

![Crash Doctor](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/6.png)

</div>

### 📦 Smart Project Management

Organize multiple Minecraft projects with ease. Each project maintains its own mod configuration, version, and settings. Switch between modpacks instantly without manual setup.

<div align="center">

![Project Manager](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/3.png)

</div>

### 🎨 Beautiful Modern Interface

Experience a cosmic-themed UI designed for both functionality and aesthetics. Smooth animations, intuitive navigation, and a clean design make mod management enjoyable rather than frustrating.

<div align="center">

![Main Interface](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/1.png)

</div>

### 👤 Personalized Experience

View and customize your Minecraft skin directly in the launcher. The integrated skin viewer and wardrobe let you preview changes before applying them to your account.

<div align="center">

![Skin Viewer](https://raw.githubusercontent.com/TheVirusNVGM/astral-ai-launcher-releases/master/screenshots/2.png)

</div>

---

## Key Features

### AI Capabilities

- **Intelligent Mod Selection** - AI understands mod relationships and compatibility
- **Semantic Search** - Find mods by description, not just keywords
- **Auto-Categorization** - Automatically organize mods into logical categories
- **Context-Aware Suggestions** - Get mod recommendations based on your existing setup
- **Dependency Resolution** - Automatic handling of required dependencies and conflicts

### Mod Management

- **Visual Drag & Drop Board** - Intuitive mod organization
- **Category Management** - Create custom categories and organize visually
- **Auto-Sort** - Let AI categorize your mods automatically
- **Export & Import** - Share modpacks as JSON files
- **Mod Browser** - Search and add mods directly from Modrinth

### Performance & Reliability

- **Built with Rust + Tauri** - Native performance, minimal resource usage
- **Fast Startup** - Optimized loading times
- **Efficient Storage** - Smart caching and dependency management
- **Crash Prevention** - AI-powered conflict detection before launch

### Compatibility

- **All Loaders Supported** - Fabric, Forge, NeoForge, Quilt
- **Cross-Loader Compatibility** - Mix Fabric and Fabric+ mods intelligently
- **Version Management** - Handle multiple Minecraft versions seamlessly
- **Update Detection** - Automatic mod update notifications

---

## Download & Installation

### System Requirements

- **OS**: Windows 10/11 (64-bit)
- **RAM**: 4 GB minimum (8 GB recommended)
- **Minecraft**: Java Edition (any version)
- **Internet**: Required for authentication and mod downloads

### Installation Steps

1. **Download** the latest MSI installer from [Releases](https://github.com/TheVirusNVGM/astral-ai-launcher-releases/releases)
2. **Run** the installer (`ASTRAL-AI Launcher_xxx_x64_en-US.msi`)
3. **Launch** the application
4. **Sign in** with your ASTRAL-AI account (or create one)
5. **Start** creating your first AI-powered modpack!

---

## Quick Start Guide

### Creating Your First AI Modpack

1. Click **"New Project"** from the main menu
2. Select your Minecraft version and mod loader
3. Open the **Visual Board** (drag & drop interface)
4. Click the **AI Panel** button (sparkles icon)
5. Type your modpack idea, e.g., *"Create a magic-themed modpack with exploration"*
6. Wait for AI to generate your modpack (usually 1-3 minutes)
7. Review and adjust mods on the board
8. Click **"Launch"** to start playing!

### Using Crash Doctor

1. If your game crashes, return to the launcher
2. Click the **"Crash Doctor"** button in the toolbar
3. Wait for AI analysis (reads crash logs automatically)
4. Review suggested fixes
5. Select fixes to apply and click **"Apply Fixes"**
6. Launch again with resolved conflicts

### Organizing Mods Visually

- **Drag mods** between categories on the board
- **Create categories** by right-clicking empty space
- **Use Auto-Sort** to let AI categorize mods automatically
- **Search mods** using the search panel
- **Filter by category** to focus on specific mod types

---

## Why Choose ASTRAL-AI Over Other Launchers?

| Feature | ASTRAL-AI | Traditional Launchers |
|---------|-----------|----------------------|
| **AI Modpack Generation** | ✅ Yes | ❌ No |
| **Visual Mod Board** | ✅ Drag & drop | ❌ File-based |
| **AI Crash Analysis** | ✅ Crash Doctor | ❌ Manual debugging |
| **Semantic Mod Search** | ✅ 50,000+ mods | ❌ Keyword only |
| **Auto Dependency Resolution** | ✅ Intelligent | ⚠️ Basic |
| **Cross-Loader Compatibility** | ✅ Smart detection | ❌ Manual |
| **Performance** | ✅ Rust backend | ⚠️ Varies |
| **Modern UI** | ✅ Cosmic theme | ⚠️ Outdated |

### What Makes Us Different

- **AI-First Approach**: We don't just add AI as a feature—it's core to how the launcher works
- **Visual Management**: See your entire modpack structure at once, not buried in folders
- **Proactive Problem Solving**: Crash Doctor fixes issues before you even know they exist
- **Context Understanding**: AI understands mod relationships, not just names
- **Production-Ready**: Built for real-world use with 50,000+ mods in the database

---

## Authentication & Accounts

ASTRAL-AI Launcher uses secure OAuth 2.0 authentication. Your account gives you access to:

- **Free Tier**: Basic modpack building and management
- **Premium Tier**: Advanced AI features, Crash Doctor, priority support
- **Pro Tier**: Unlimited AI requests, early access features

Sign in once, and your projects sync across devices (coming soon).

---

## Technical Details

### Architecture

- **Frontend**: React + TypeScript + Vite
- **Backend**: Rust + Tauri (native performance)
- **AI Backend**: Python + Flask (RAG architecture with pgvector)
- **Database**: PostgreSQL + Supabase (50,000+ mods indexed)
- **AI Models**: DeepSeek R1, OpenAI GPT-4, Claude Sonnet

### AI Technology

- **RAG System**: Retrieval-Augmented Generation for accurate mod suggestions
- **Vector Search**: pgvector for semantic similarity matching
- **Hybrid Search**: Combines vector embeddings with BM25 keyword search
- **Conditional Architecture**: Adapts pipeline based on request complexity

---

## Support & Community

### Getting Help

- Check existing [Issues](https://github.com/TheVirusNVGM/astral-ai-launcher-releases/issues)
- Report bugs via GitHub Issues
- Join our Discord community
- Contact support through the launcher

### Contributing

We welcome contributions! Check out our main repository for development guidelines.

---

## Updates

The launcher automatically checks for updates on startup. New versions include:

- AI model improvements
- New features and UI enhancements
- Bug fixes and performance optimizations
- Expanded mod database

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- [Tauri](https://tauri.app/) - Amazing desktop app framework
- [Nitrolaunch](https://github.com/Nickthegamer24/nitrolaunch) - Minecraft launching capabilities
- [Modrinth](https://modrinth.com/) - Mod database and API
- DeepSeek, OpenAI, Anthropic - AI models powering intelligent features

---

**Made with ❤️ by the ASTRAL-AI Team**

*Experience Minecraft modding like never before.*
