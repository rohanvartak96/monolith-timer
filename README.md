# Monolith — The Timeless Timer

A minimal, elegant countdown timer built as a Progressive Web App. No installs, no ads, no accounts — just open and time.

## Features

- **20 synthesized chimes** via Web Audio API (no external audio files)
- **Custom time presets** — edit labels and durations in Settings
- **Custom time picker** — set any hour/minute/second combination
- **Visual state feedback** — color transitions for running, danger (last 10s), done, and paused states
- **Progress bar** — thin line at the top filling as the countdown runs (toggleable)
- **Digit flip animation** — optional animated digit transitions
- **Volume control** + speaker mute toggle
- **Dark / light mode** — follows system preference
- **Haptic feedback** on completion
- **Offline support** via service worker
- **Installable** on iOS, Android, and desktop (PWA manifest)

## Usage

Open `monolith-timer.html` directly in any modern browser — no build step or server required.

To install as a PWA, serve the files over HTTPS and use your browser's "Add to Home Screen" / "Install" option.

## Files

| File | Description |
|------|-------------|
| `monolith-timer.html` | Entire app — HTML, CSS, and JS in one file |
| `manifest.json` | PWA manifest |
| `sw.js` | Service worker for offline caching |
| `icon-180.png` | Apple touch icon |
| `icon-192.png` | PWA icon (192×192) |
| `icon-512.png` | PWA icon (512×512) |
