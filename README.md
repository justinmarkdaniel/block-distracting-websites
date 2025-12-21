# Block Distracting Websites

A minimalist Chrome extension that blocks distracting websites and replaces them with motivational quotes.

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-green)

## Features

- Block any website by domain
- Clean, distraction-free blocked page
- 75 curated quotes from entrepreneurs, creators, and thinkers
- Zero configuration required
- No tracking, no analytics, no external requests

## Installation

1. Clone this repository
2. Open `chrome://extensions/` in Chrome
3. Enable "Developer mode" (top right)
4. Click "Load unpacked"
5. Select the cloned folder

## Usage

1. Click the extension icon
2. Enter a domain (e.g., `twitter.com`)
3. Click "Block Site"

When you visit a blocked site, you'll see a motivational quote instead.

## Files

```
├── manifest.json      # Extension configuration
├── popup.html/css/js  # Settings interface
├── blocked.html/js    # Blocked page with quotes
├── background.js      # URL redirect rules
└── icon*.png          # Extension icons
```

## License

See [LICENSE](LICENSE) for details. Personal use only.

