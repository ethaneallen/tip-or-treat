# 💵 Tip & Split Calculator

A clean, lightweight tip and bill-splitting calculator built as a single-page Progressive Web App (PWA). No frameworks, no dependencies — just HTML, CSS, and JavaScript.

## ✨ Features

- **Tip by percentage or amount** — enter a tip % and the dollar amount updates automatically, or type a custom tip amount and the percentage syncs back
- **Bill splitting** — divide the total evenly across any number of people
- **Installable PWA** — add it to your home screen and use it offline like a native app
- **Mobile-first design** — responsive layout optimized for phones, works great on desktop too
- **Zero dependencies** — a single HTML file with inline CSS and JS

## 📸 Preview

| Input your bill | Adjust tip & split |
|---|---|
| Enter the bill amount, choose a tip %, and set the number of people | See the total and per-person cost update instantly |

## 🚀 Getting Started

### Use it directly

Open `tip-split.html` in any modern browser — that's it. No build step, no server required.

### Install as a PWA

1. Open the app in Chrome, Edge, or Safari
2. Tap **"Add to Home Screen"** (or the install icon in the address bar)
3. Use it offline anytime

### Host it

Drop all three files into any static hosting (GitHub Pages, Netlify, Vercel, etc.):

```
tip-split.html   ← the app
manifest.json    ← PWA metadata
sw.js            ← service worker for offline support
```

## 🛠 How It Works

| Input | Effect |
|---|---|
| **Bill Amount** | Base amount before tip |
| **Tip Percent** | Calculates tip from the bill (use +/- buttons or type directly) |
| **Tip Amount** | Override the tip in dollars — the percent adjusts to match |
| **No. of People** | Splits the total (bill + tip) evenly |

The **Total Amount** and **Each Person Pays** fields update in real time as you change any input.

## 📁 Project Structure

```
tip-split/
├── tip-split.html   # Full app (HTML + CSS + JS)
├── manifest.json    # Web app manifest for PWA
├── sw.js            # Service worker (caching & offline)
└── README.md
```

## 📄 License

Free to use and modify.
