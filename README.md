# TXNT Reader

A modern EPUB reader with built-in translation capabilities for Japanese, Spanish, and Malayalam to English.

![TXNT Reader Logo](assets/icon.png)

## Features

- 📚 **Clean EPUB Reading** - Read EPUB files with beautiful formatting
- 🌐 **Smart Translation** - Translate Japanese, Spanish, and Malayalam to English
- 🖱️ **Click-to-Translate** - Click any text for instant translation
- 🔄 **Auto-Translate** - Automatically translate entire pages
- 🎨 **Modern UI** - Dark theme with orange accents
- ⚡ **Fast & Reliable** - Google Translate with local dictionary fallback
- 🖼️ **Image Support** - Display images from EPUB files
- 📖 **Table of Contents** - Easy chapter navigation
- ⚙️ **Customizable** - Adjustable font size, line height, and themes

## Translation Methods

- **🟢 Google Translate** - High-quality online translation (requires internet)
- **🟠 Smart Dictionary** - Reliable offline translation with contextual phrases

## Supported Languages

- **Japanese** (日本語) → English
- **Spanish** (Español) → English  
- **Malayalam** (മലയാളം) → English

## Installation

### Option 1: Download Executable (Recommended)
1. Go to [Releases](../../releases)
2. Download `TXNT-Reader-Setup-1.0.0.exe` for Windows
3. Run the installer and follow the setup wizard
4. Launch TXNT Reader from your desktop or start menu

### Option 2: Portable Version
1. Download `TXNT-Reader-Portable-1.0.0.exe` from [Releases](../../releases)
2. Run directly - no installation required

### Option 3: Build from Source
```bash
# Clone the repository
git clone https://github.com/yourusername/txnt-reader.git
cd txnt-reader

# Install dependencies
npm install

# Run in development mode
npm start

# Build executable
npm run build
```

## Usage

1. **Open EPUB File**: Click "Open EPUB" to select your book
2. **Select Translation Language**: Choose from the dropdown (Japanese → English, etc.)
3. **Manual Translation**: Click any text to see translation in a popup
4. **Auto Translation**: Select a language to automatically translate the entire page
5. **Navigation**: Use Previous/Next buttons or Table of Contents

## Screenshots

### Main Interface
![Main Interface](screenshots/main-interface.png)

### Translation in Action
![Translation](screenshots/translation-demo.png)

## Technical Details

- **Built with**: Electron, JavaScript, HTML5, CSS3
- **EPUB Parsing**: JSZip for file extraction and parsing
- **Translation**: Google Translate API with local dictionary fallback
- **Supported Formats**: EPUB 2.0 and 3.0
- **Platform**: Windows (primary), macOS and Linux (experimental)

## Development

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Setup
```bash
npm install
npm start
```

### Building
```bash
# Build for current platform
npm run build

# Build for Windows specifically
npm run build-win
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Translate API for high-quality translations
- Electron framework for cross-platform desktop apps
- JSZip library for EPUB file parsing
- The open-source community for inspiration and tools

## Support

If you encounter any issues or have suggestions:
1. Check the [Issues](../../issues) page
2. Create a new issue with detailed information
3. Include your operating system and TXNT Reader version

---

**Made with ❤️ for language learners and book enthusiasts**