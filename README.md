# Pigeon

Browser-based security tools — password, passphrase, PIN and username generator. No account, no server, no tracking. Everything runs locally in your browser.

**Live site:** [pigeonofficial.vercel.app](https://pigeonofficial.vercel.app)
**Chrome extension:** [ZavionGames/Pigeon-Extensions](https://github.com/ZavionGames/Pigeon-Extensions)
**Privacy policy:** [pigeonofficial.vercel.app/privacy](https://pigeonofficial.vercel.app/privacy)

---

## Features

- **Password generator** — 8–64 characters, uppercase, lowercase, numbers, symbols, exclude similar characters
- **Passphrase generator** — 3–8 words with customizable separator
- **PIN generator** — 4–12 digits
- **Username generator** — adjective+noun, word+number styles
- **Password compare** — compare two passwords with entropy-based strength estimation
- **Strength meter** — entropy in bits
- **Dark / light theme** — respects system preference, toggleable
- Cryptographically random via `crypto.getRandomValues`
- Auto-regenerates on every option change

## Usage

Open `index.html` in any browser. No build step, no dependencies.

Or visit: [pigeonofficial.vercel.app](https://pigeonofficial.vercel.app)

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Main UI |
| `styles.css` | Styling |
| `script.js` | Generation logic and UI |
| `privacy.html` | Privacy policy |
| `Pigeon-Logo.png` | Favicon / logo |
| `404.html` | Custom 404 (Vercel) |
| `sitemap.xml` | Sitemap |
| `site.webmanifest` | PWA manifest |
| `vercel.json` | Vercel config, security headers |

## Privacy

Pigeon collects no data. Passwords are generated locally and never leave your browser. The only value stored is your theme preference (`localStorage`). See the full [privacy policy](https://pigeonofficial.vercel.app/privacy).

## License

MIT
