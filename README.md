# VP BIBLE v2.4.1

**Professional Church Projection Software**

VP Bible is a comprehensive desktop application designed for churches to manage and display Bible verses, worship media, and live streaming integration with vMix/OBS Studio.

## Features

- 📖 **Bible Display** - Display Bible verses with multiple translations
- 🎬 **Media Library** - Manage videos, backgrounds, and lyric slides
- 🎤 **Live Audio** - Stream microphone audio via NDI
- 🌐 **vMix Integration** - Direct browser input support
- 📡 **NDI Output** - Professional streaming output
- 🎨 **Customizable UI** - Dark theme with gold accents
- ⌨️ **Keyboard Shortcuts** - Fast navigation and control
- 🎙️ **Voice Commands** - Hands-free control
- 💾 **Offline Mode** - Works without internet connection
- 🔒 **Secure** - Encrypted data storage

## Quick Start

### Installation

1. Clone the repository:
```bash
git clone https://github.com/princeferdinand12-bit/vp-bible.git
cd vp-bible
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Usage

### Basic Setup

1. Open `index.html` in your browser or run the Electron app
2. The app will automatically connect to available streaming software
3. Use the media library to add content
4. Display Bible verses or media
5. Send to live output

### vMix Integration

1. Copy the localhost URL from the help section
2. Add as Browser Input in vMix
3. Configure NDI output settings
4. Use the "Send to Live" button to broadcast

### Keyboard Shortcuts

- `Ctrl + K` - Search scriptures
- `Ctrl + B` - Bookmark current verse
- `Ctrl + F` - Find in Bible
- `Space` - Play/Pause audio
- `←/→` - Previous/Next verse
- `Esc` - Close dialog

## Project Structure

```
vp-bible/
├── index.html           # Main application UI
├── help-center.html     # Help and support documentation
├── ui-mockup.html       # UI mockups for reference
├── package.json         # Dependencies and scripts
├── main.js             # Electron main process (if using Electron)
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Desktop**: Electron (optional)
- **Streaming**: vMix/OBS WebSocket API
- **Bible Data**: Bible API (https://bible-api.com)
- **NDI**: Network Device Interface

## Configuration

Create a `.env` file in the root directory:

```env
VITE_API_URL=http://localhost:3000
VITE_BIBLE_API=https://bible-api.com
VITE_OBS_HOST=localhost
VITE_OBS_PORT=4444
VITE_VMIX_HOST=localhost
VITE_VMIX_PORT=8099
```

## Support

- 📧 Email: support@vp.bible
- 🌐 Website: https://vp.bible
- 💬 Live Chat: Available in Help Center
- 📖 Documentation: https://help.vp.bible/docs

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please read our contributing guidelines and submit pull requests to our repository.

## Changelog

### v2.4.1
- Added Help Center with voice commands and keyboard shortcuts
- Improved UI mockups and visual design
- Enhanced vMix integration
- Better media library management
- Fixed audio streaming issues

### v2.4.0
- Initial release
- Bible verse display
- Media management
- Live streaming support
- NDI output

## Credits

Developed with ❤️ for churches and worship teams worldwide.

---

**Version:** 2.4.1  
**Last Updated:** 2024  
**Status:** Active Development
