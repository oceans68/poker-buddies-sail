# 🃏 POKER BUDDIES SAIL

> **ניהול מפגשי פוקר מאת יוחאי אהרון**  
> Friendly poker cash-game manager for sailing trips — built for the sea ⛵

---

## 🌐 Live App

**[▶ פתח את האפליקציה](https://YOUR-USERNAME.github.io/poker-buddies-sail/)**

> Replace `YOUR-USERNAME` with your GitHub username after deploying.

---

## 📱 What is this?

A single-file Hebrew PWA-style web app for managing friendly poker cash games during a sailing trip.  
No backend, no database — everything runs in the browser and saves to `localStorage`.

### Features

- 🏠 **Multi-trip lobby** — manage multiple sailing trips
- 🌙 **Evening management** — track buy-ins, rebuys, and cash-outs per night
- 👤 **Per-night player management** — add/remove players per evening
- 📊 **Live balance checker** — warns if total buy-ins ≠ cash-outs
- 💸 **Automatic settlement** — minimum-transfer algorithm calculates who pays whom
- 📈 **Chart.js chart** — cumulative profit/loss graph per player across nights
- 📥 **Excel export** — export evening or full trip to `.xls`
- 📋 **WhatsApp share** — one-tap copy of results for group chat
- 💾 **JSON backup/restore** — export and import full trip data
- 🎵 **Chip sounds** — fun Web Audio API sound on every buy-in
- 🌊 **Greek island design** — Santorini/Mykonos blue & white palette

### Default Players
גידי · אלון · אלי · יוחאי · גל · מיקי

---

## 🚀 Deploy to GitHub Pages (step by step)

See full instructions in [DEPLOY.md](./DEPLOY.md)

---

## 🗂 File Structure

```
poker-buddies-sail/
├── index.html      ← The entire app (single self-contained file)
├── README.md       ← This file
└── DEPLOY.md       ← Step-by-step GitHub Pages deployment guide
```

---

## 🛠 Tech Stack

- Vanilla HTML + CSS + JavaScript (no framework)
- `localStorage` for data persistence
- Chart.js (loaded from CDN, with offline fallback)
- Web Audio API for chip sounds
- Inline SVG for logo and wave graphics

---

## 📄 License

MIT — free to use, share, and modify.  
Built with ❤️ for a group of friends on a Greek sailing trip.
