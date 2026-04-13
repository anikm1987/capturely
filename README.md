# 🔴 Capturely

**Record screen demos with voice — instantly.**

A lightweight, zero-dependency screen recorder that runs entirely in your browser. No installs, no sign-ups, no servers. Just open and record.

[**Try it live →**](https://yourusername.github.io/capturely)

---

## Features

- **Screen + Voice** — Capture your screen with microphone narration in one click
- **Tab Audio** — Optionally capture system/tab audio (Chrome)
- **Countdown** — 3-2-1 countdown so you're never caught off-guard
- **Pause & Resume** — Take a breather mid-recording without starting over
- **Instant Preview** — Watch your recording back before saving
- **Download** — Save as `.webm` with one click
- **Native Share** — Share directly to apps via the Web Share API (mobile & supported browsers)
- **100% Private** — Everything stays in your browser. Nothing is uploaded anywhere.

## How It Works

1. Open Capturely in your browser
2. Toggle mic / tab audio as needed
3. Click **Start Recording** → pick a screen, window, or tab
4. A 3-2-1 countdown begins, then you're live
5. Hit **Stop** when done → preview, download, or share

## Deploy Your Own

Capturely is a single `index.html` file. No build step required.

### GitHub Pages (recommended)

```bash
git clone https://github.com/yourusername/capturely.git
cd capturely
# index.html is already in the root — just push
git push origin main
```

Then go to **Settings → Pages → Source: main branch** and your app is live.

### Other Options

- **Netlify / Vercel** — Drag and drop the file, done
- **Local** — Just double-click `index.html` to open in your browser

## Browser Support

| Browser | Screen | Mic | Tab Audio |
|---------|--------|-----|-----------|
| Chrome / Edge | ✅ | ✅ | ✅ |
| Firefox | ✅ | ✅ | ❌ |
| Safari | ✅ | ✅ | ❌ |

Tab audio capture requires Chromium-based browsers and only works when sharing a browser tab.

## Tech

- Vanilla HTML + CSS + JavaScript
- `getDisplayMedia()` for screen capture
- `getUserMedia()` for microphone
- `MediaRecorder` API for encoding
- `AudioContext` for mixing audio streams
- Web Share API for native sharing
- Zero dependencies. Zero frameworks. One file.

## License

MIT — do whatever you want with it.

---

Made with Capturely. That's it. That's the tool.
