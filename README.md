# iWellny Website

Official website for iWellny - Your Complete Wellness Companion iOS app.

🌐 **Live:** [https://iwellny.com](https://iwellny.com)

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Home | `/` | Landing page with app showcase, features, and App Store download |
| About | `/about` | Developer story, key features, and technologies used |
| Support | `/support` | FAQ, troubleshooting, and contact information |
| Privacy | `/privacy` | Privacy policy and data handling practices |
| Terms | `/terms` | Terms of service and audio content licensing |

## Tech Stack

- **Hosting:** GitHub Pages
- **Framework:** Static HTML/CSS/JS (no build tools required)
- **Fonts:** [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- **Icons:** Custom SVG icons (SF Symbols style)

## Features

- 🎨 Glass-morphic design with dark blue theme
- ✨ Animated gradient backgrounds and particle effects
- 📱 Fully responsive (mobile, tablet, desktop)
- 🖼️ 15-slide phone screenshot carousel
- 🔗 Clean URLs (folder-based structure)

## File Structure

```
iwellny.com/
├── index.html              # Home page
├── README.md               # This file
├── android-chrome-512x512.png  # App icon/favicon
├── favicon.ico
├── profile_photo.jpg       # Developer photo (About page)
├── screenshot-1.jpg        # App screenshots (1-15)
├── screenshot-2.jpg
├── ...
├── about/
│   └── index.html          # About page
├── privacy/
│   └── index.html          # Privacy Policy
├── support/
│   └── index.html          # Support/FAQ
└── terms/
    └── index.html          # Terms of Service
```

## Screenshots

Place your app screenshots in the root directory:
- `screenshot-1.jpg` - Home Screen
- `screenshot-2.jpg` - Sound Mixer
- `screenshot-3.jpg` - Guided Meditation
- `screenshot-4.jpg` - Sleep Timer
- `screenshot-5.jpg` - Wellness Dashboard
- `screenshot-6.jpg` - Pomodoro Timer
- `screenshot-7.jpg` - Full Screen Player
- `screenshot-8.jpg` - Ambient Scenes
- `screenshot-9.jpg` - Detailed Wellness
- `screenshot-10.jpg` - Wellness Goals
- `screenshot-11.jpg` - Memory Sounds
- `screenshot-12.jpg` - Soundscape Map
- `screenshot-13.jpg` - Widgets
- `screenshot-14.jpg` - Achievements
- `screenshot-15.jpg` - Rewards

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
```

## Deployment

Push to the `main` branch — GitHub Pages will automatically deploy.

## License

© 2026 iWellny. All rights reserved.

---

**Contact:** [support@iwellny.com](mailto:support@iwellny.com)
