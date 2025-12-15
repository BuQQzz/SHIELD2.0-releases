# SHIELD - Official Releases

Welcome to the official releases repository for **SHIELD** - a privacy-first, local AI chatbot for Windows with tool integration capabilities.

## 📥 Download

Head to the [**Releases**](https://github.com/BuQQzz/SHIELD2.0-releases/releases) page to download the latest version of SHIELD.

### Latest Release: v0.1.3 - Model Download System Overhaul

**[Download v0.1.3](https://github.com/BuQQzz/SHIELD2.0-releases/releases/tag/v0.1.3)**

- **SHIELD-0.1.3-x64.exe** - Standard Windows installer (recommended)
- **SHIELD-0.1.3-portable.exe** - Portable version (no installation)

## 🛡️ What is SHIELD?

SHIELD is a **privacy-first** Windows desktop application that brings AI assistance directly to your PC. All AI processing happens locally on your machine - no data is sent to external servers.

### Key Features

- 🔒 **100% Local** - All AI inference runs on your PC
- 🤖 **Multiple AI Models** - Support for Qwen, Llama, Mistral, Phi-3, Gemma, and more
- 🔍 **Web Search Integration** - AI can search the web to provide up-to-date information
- 🛠️ **Tool Integration** - MCP (Model Context Protocol) support for file operations
- 💬 **Conversation Management** - Save, search, and organize your chats
- 🎨 **Modern UI** - Clean, minimalistic interface built with React
- 🌐 **Offline Capable** - Works without internet (except for model downloads and web search)

## 📋 System Requirements

- **OS**: Windows 10 or later (64-bit)
- **RAM**: 8GB minimum (16GB recommended for larger models)
- **Storage**: 5GB+ free disk space for AI models
- **GPU**: Optional but recommended (CUDA-capable NVIDIA GPU for faster inference)

## 🚀 Getting Started

1. **Download** the installer from the [Releases](https://github.com/BuQQzz/SHIELD2.0-releases/releases) page
2. **Run** the installer (or portable executable)
3. **Launch** SHIELD
4. **Download** your first AI model from the in-app model browser
5. **Start** chatting with your local AI assistant!

### First-Time Setup

When you first launch SHIELD:
1. Click **"Download Models"** in the header
2. Select a model:
   - **Recommended for beginners**: Qwen 2.5 3B Instruct (1.9GB, free to download)
   - **Best balanced**: Qwen 2.5 7B Instruct (4.2GB, free to download)
3. Wait for download to complete
4. Start chatting!

### HuggingFace Token (For Gated Models)

Some models require a HuggingFace token:
- Meta Llama models (3.3 70B, 3.2 3B, 3.2 1B)
- Mistral models (Large 2, 7B Instruct)
- Microsoft Phi-3 Medium 14B
- Google Gemma 2 9B
- DeepSeek Coder 7B

To set up:
1. Create account at [huggingface.co](https://huggingface.co)
2. Accept model license agreements
3. Generate token with "Read access to gated repos" permission
4. Add token in **Settings → System → HuggingFace Token**

## 📖 Documentation

For detailed guides and troubleshooting, please refer to the main documentation (available in the source repository for contributors).

## 🔄 Updates

SHIELD checks for updates automatically. You'll be notified when a new version is available.

Manual update process:
1. Download the latest installer
2. Run it - your settings, conversations, and models will be preserved
3. No need to uninstall the previous version

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please open an issue in this repository!

## 📜 License

SHIELD is released under the MIT License.

## 🔒 Privacy

SHIELD is built with privacy as the top priority:
- ✅ All AI inference happens locally on your machine
- ✅ No telemetry or analytics
- ✅ No data sent to external servers (except optional web search)
- ✅ Your conversations stay on your PC
- ✅ Open source and auditable

---

**Made with ❤️ for privacy-conscious users**

**Version**: 0.1.3 | **Last Updated**: December 13, 2025
