# Suno Desktop

A tiny, unofficial macOS desktop wrapper for [suno.com](https://suno.com) —
just the real site in its own native window, with a persistent login
session, instead of a browser tab.

Not affiliated with Suno. No scraping, no reverse-engineered API — every
feature works because it's simply the actual web app.

## Install

Download the build for your platform from [Releases](../../releases):

- **macOS** (Apple Silicon or Intel): the `.dmg`, then drag **Suno.app** to Applications
- **Windows**: `Suno.Setup.1.0.0.exe`
- **Linux**: the `.AppImage` (make it executable first) or the `.deb`

Builds are unsigned/unnotarized, so the OS will warn on first launch:
- **macOS**: right-click the app → **Open** → **Open**
- **Windows**: click **More info** → **Run anyway** on the SmartScreen prompt
- **Linux AppImage**: `chmod +x Suno-1.0.0.AppImage` before running

## Build from source

```bash
npm install
npm start   # run it
npm run build   # produces dist/Suno-<version>-arm64.dmg
```

## License

MIT — see [LICENSE](LICENSE).
