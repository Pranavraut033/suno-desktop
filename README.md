# Suno Desktop

A tiny, unofficial macOS desktop wrapper for [suno.com](https://suno.com) —
just the real site in its own native window, with a persistent login
session, instead of a browser tab.

Not affiliated with Suno. No scraping, no reverse-engineered API — every
feature works because it's simply the actual web app.

## Install

Download the latest `.dmg` from [Releases](../../releases), open it, and
drag **Suno.app** to Applications.

The app is unsigned (no Apple Developer certificate), so the first launch
will be blocked by Gatekeeper. Right-click the app → **Open** → **Open**
to bypass this one-time warning.

## Build from source

```bash
npm install
npm start   # run it
npm run build   # produces dist/Suno-<version>-arm64.dmg
```

## License

MIT — see [LICENSE](LICENSE).
