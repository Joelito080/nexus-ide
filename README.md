# Nexus IDE v1.0.0

> **AI-Powered Developer Workspace** | Modern, Fast, and Developer-Friendly

[![Release](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/Joelito080/nexus-ide/releases/tag/v1.0.0)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![GitHub Issues](https://img.shields.io/github/issues/Joelito080/nexus-ide)](https://github.com/Joelito080/nexus-ide/issues)

---

## Overview

**Nexus IDE** is a modern desktop code editor built with Electron, React, and TypeScript. It combines the power of Monaco Editor with intelligent AI assistance, seamless Git integration, and professional developer tools—all in a lightweight, responsive application.

Whether you're building web applications, backend services, or exploring new languages, Nexus IDE provides an enhanced coding experience with built-in AI assistance, version control workflows, and comprehensive development utilities.

---

## 🌟 Feature Highlights

### 🤖 AI-Powered Development
- **Multi-Provider Support**: OpenAI (OpenCode), Ollama (local models), and Google Gemini
- **Intelligent Code Completion**: Context-aware suggestions and auto-completions
- **Code Generation**: Describe tasks in natural language and let AI generate code
- **Refactoring Assistant**: AI-powered code optimization and modernization
- **Flexible Configuration**: Easy setup with built-in provider management

### 💻 Professional Editor
- **Monaco Editor**: Industry-standard code editing experience
- **100+ Languages**: Full syntax highlighting for all major programming languages
- **Code Formatting**: Integrated code formatting and linting
- **Multi-Tab Workflow**: Work with multiple files seamlessly
- **Customizable Theme**: Light and dark mode with adjustable colors

### ⚡ Developer Productivity
- **Command Palette** (`Ctrl+Shift+P`): Quick access to all IDE features
- **Global Search**: Full-text search with regex support and replace
- **File Navigation**: Rapid file finding and project exploration
- **Keyboard Shortcuts**: Extensive customizable keyboard bindings

### 🔄 Git Integration
- **Full Git Support**: Stage, commit, push, pull directly in the IDE
- **Branch Management**: Create, switch, merge, and delete branches
- **Diff Viewer**: Visual comparison of changes before committing
- **Merge Conflicts**: Built-in conflict resolution editor
- **Git History**: Browse commits with detailed history explorer
- **Remote Tracking**: Manage remote repositories and tracking branches

### 💾 Data Protection & Recovery
- **Crash Recovery**: Automatic session restoration after unexpected shutdowns
- **Backup Manager**: Schedule automatic or manual project backups
- **Backup Encryption**: Optional encryption for sensitive backups
- **Recovery Dashboard**: Choose which sessions and backups to restore
- **Unsaved Changes Detection**: Never lose your work

### 📊 Diagnostics & Monitoring
- **Performance Dashboard**: Real-time CPU, memory, and disk metrics
- **System Information**: Detailed environment configuration
- **Error Logging**: Comprehensive error tracking and reporting
- **Health Monitoring**: Track extension and dependency status
- **Debug Tools**: Built-in DevTools for troubleshooting

---

## 📥 Installation

### Windows

#### Option 1: Installer (Recommended)
1. Download `nexus-ide-1.0.0-setup.msi` from [Releases](https://github.com/Joelito080/nexus-ide/releases)
2. Run the installer and follow the wizard
3. Launch from Start Menu or Desktop

**Features**: Start Menu shortcuts, system-level installation, easy uninstall

#### Option 2: Portable Build
1. Download `nexus-ide-1.0.0-portable.exe` from [Releases](https://github.com/Joelito080/nexus-ide/releases)
2. Run directly—no installation required
3. Run from any location including USB drives

**Features**: No installation, instant launch, portable between machines

### macOS

1. Download `nexus-ide-1.0.0.dmg` from [Releases](https://github.com/Joelito080/nexus-ide/releases)
2. Open the DMG file
3. Drag Nexus IDE to Applications folder
4. Launch from Applications

**System Requirements**: macOS 10.13 or later

### Linux

#### Universal (Recommended)
1. Download `nexus-ide-1.0.0.AppImage` from [Releases](https://github.com/Joelito080/nexus-ide/releases)
2. Make it executable: `chmod +x nexus-ide-1.0.0.AppImage`
3. Run: `./nexus-ide-1.0.0.AppImage`

#### Ubuntu/Debian
```bash
sudo apt install ./nexus-ide-1.0.0.deb
nexus-ide
```

#### Fedora/RHEL
```bash
sudo rpm -i nexus-ide-1.0.0.rpm
nexus-ide
```

---

## 🚀 Quick Start

### First Time Setup

1. **Launch Nexus IDE**
   - Open the application from your system launcher

2. **Create or Open a Project**
   - File → Open Folder, or drag a folder into the window

3. **Configure AI (Optional)**
   - Settings → AI Providers
   - Select your preferred provider and enter credentials
   - Test the connection

4. **Start Coding**
   - Open a file and begin editing
   - Use Command Palette (`Ctrl+Shift+P`) to explore features

### Configuration

#### AI Provider Setup

**Option 1: OpenAI (OpenCode)**
- Sign up at [platform.openai.com](https://platform.openai.com)
- Create an API key
- Settings → AI Providers → OpenAI
- Paste your API key and save

**Option 2: Ollama (Local Models)**
- Download [Ollama](https://ollama.ai)
- Install and run: `ollama serve`
- Settings → AI Providers → Ollama
- Verify connection to local server

**Option 3: Google Gemini**
- Get API key from [ai.google.dev](https://ai.google.dev)
- Settings → AI Providers → Gemini
- Paste your API key and save

#### Git Configuration

1. Open a folder containing a Git repository
2. The Git panel appears automatically
3. Enter your credentials when prompted
4. You're ready to commit, push, and pull!

**Note**: Ensure Git is installed on your system (`git --version`)

---

## 📸 Screenshots

*Screenshots placeholders - Add these to your release:*

- **Main Editor**: Clean interface with Monaco Editor
- **AI Panel**: Easy provider configuration and chat interface
- **Git Panel**: Staging area, commit history, branch management
- **Command Palette**: Quick command access and search
- **Settings**: Dark and light theme previews
- **Diagnostics Dashboard**: Performance and system monitoring

---

## 🛠️ Troubleshooting

### General Issues

**Q: The application won't start**
- A: Check system requirements (4GB RAM minimum, 500MB free space)
- Verify OS compatibility (Windows 10+, macOS 10.13+, Ubuntu 16.04+)
- Try launching from command line to see error messages

**Q: How do I report a bug?**
- A: Go to [GitHub Issues](https://github.com/Joelito080/nexus-ide/issues)
- Click "New Issue" and select "Bug Report"
- Provide detailed steps to reproduce

**Q: Where are my settings stored?**
- A: Settings are stored in the application data directory:
  - Windows: `%APPDATA%/Nexus IDE`
  - macOS: `~/Library/Application Support/Nexus IDE`
  - Linux: `~/.config/Nexus IDE`

### AI Integration Issues

**Q: AI completion isn't working**
- A: Verify API credentials in Settings → AI Providers
- Check internet connection
- Confirm API key validity and account has credits
- For Ollama: ensure `ollama serve` is running
- Check logs in Diagnostics → Error Log

**Q: How do I switch AI providers?**
- A: Settings → AI Providers → Select different provider
- Existing settings remain for each provider

**Q: Can I use multiple providers?**
- A: Yes! Configure all providers you want to use
- Easily switch between them in Settings

### Git Integration Issues

**Q: Git panel not showing**
- A: Ensure the folder contains a `.git` directory
- Try closing and reopening the folder
- Verify Git is installed: `git --version`

**Q: Authentication errors when pushing**
- A: Update credentials in Git panel settings
- For SSH: ensure SSH key is added to ssh-agent
- For HTTPS: use personal access token instead of password

**Q: How do I handle merge conflicts?**
- A: Conflicts appear in the editor with merge markers
- Use the built-in conflict resolver UI
- Accept current, incoming, both, or manually edit
- Stage and commit after resolving

### Crash Recovery

**Q: My work disappeared after a crash**
- A: Check the Recovery Dashboard on startup
- Select sessions you want to restore
- Recovered files appear in a recovery folder

**Q: How do I enable automatic backups?**
- A: Settings → Backup Manager → Enable Automatic Backups
- Set backup frequency (daily, weekly, monthly)

---

## 📋 System Requirements

| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| **OS** | Windows 10, macOS 10.13, Ubuntu 16.04 | Latest stable OS |
| **RAM** | 4 GB | 8 GB |
| **Storage** | 500 MB free | 2 GB free |
| **Internet** | Required for AI features | Broadband recommended |

---

## 🔐 Security

- **Data Privacy**: AI requests are sent only to configured providers
- **No Telemetry**: Nexus IDE doesn't collect usage data
- **Settings Encryption**: Sensitive settings are encrypted locally
- **Backup Encryption**: Optional encryption for backup files

For security concerns, see [SECURITY.md](SECURITY.md)

---

## 📚 Developer Guides

- [CONTRIBUTING.md](CONTRIBUTING.md) - How to contribute to Nexus IDE
- [DEVELOPMENT.md](DEVELOPMENT.md) - Local development setup
- [SECURITY.md](SECURITY.md) - Vulnerability reporting
- [Release Notes](RELEASE_NOTES.md) - Latest changes and features

---

## 🗺️ Roadmap

### v1.1 (Planned Q3 2026)
- [ ] Plugin system and marketplace
- [ ] Theme customization and additional themes
- [ ] Improved performance optimizations
- [ ] Additional language servers

### v1.2 (Planned Q4 2026)
- [ ] Collaborative editing support
- [ ] Advanced debugging tools
- [ ] Database integration
- [ ] REST client

### Future Considerations
- [ ] Cloud sync for settings and projects
- [ ] Team features and workspace sharing
- [ ] Advanced project templates
- [ ] Custom AI model support

---

## 🤝 Community & Support

- **Bug Reports**: [GitHub Issues](https://github.com/Joelito080/nexus-ide/issues)
- **Feature Requests**: [GitHub Discussions](https://github.com/Joelito080/nexus-ide/discussions)
- **General Help**: [GitHub Discussions → Help](https://github.com/Joelito080/nexus-ide/discussions)
- **Security**: [SECURITY.md](SECURITY.md)

---

## 📄 License

Nexus IDE is licensed under the [MIT License](LICENSE)

---

## 🙌 Acknowledgments

Built with:
- [Electron](https://www.electronjs.org/)
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Monaco Editor](https://monaco-editor.github.io/)
- [TypeScript](https://www.typescriptlang.org/)

Special thanks to the open-source community and beta testers.

---

**Questions? Join our [community discussions](https://github.com/Joelito080/nexus-ide/discussions) or check out the [FAQ](https://github.com/Joelito080/nexus-ide/wiki/FAQ).**

**Happy Coding! 🚀**