# WebRespring

A minimal Progressive Web App (PWA) that runs a respring-style script inside a sandboxed iframe.

## Credits
All credits go to neonmodder123 on GitHub.
You can find the original web respring files on the neonmodder123.github.io repo.

## Features
- Install-only behavior (runs only when added to Home Screen)
- Offline support via Service Worker
- Minimal UI with auto execution when launched
- Sandbox isolation using iframe

## How it works
- When opened in a browser → shows install instructions
- When installed as PWA → automatically runs the script
- Assets are cached for offline usage

## Requirements
- HTTPS hosting
- Safari (iOS) or Chromium-based browser (Android)

## Installation
1. Open the site in Safari
2. Tap Share
3. Tap "Add to Home Screen"
4. Launch from home screen

## Notes
- iOS ignores manifest icons, uses apple-touch-icon instead
- Service Worker avoids caching redirects for compatibility
- Designed for experimental / educational purposes