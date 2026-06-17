# 🏷️ Thrift Scout

**Scan anything at the thrift store. Know instantly if it's worth buying.**

- 📸 Point your camera, get an AI appraisal with live eBay sold comps in seconds
- 💰 Real resale ROI math against the tag price — before you put it in your cart
- 📝 Platform listing drafts for eBay, Poshmark, Mercari, and Facebook ready to copy

---

## ✨ Features

### Core Appraisal
- 📸 **Camera scan** — Capture any item directly from your phone
- 🤖 **AI appraisal** — Vision analysis powered by Claude (claude-sonnet-4-6)
- 📊 **Live eBay comps** — Real-time sold listings with LIVE/EST badge
- 🏷️ **Swing-ticket verdict** — Buy / Keep / Gift / Pass with 1-5 confidence rating
- 🔁 **Dupe detector** — Flags if you've scanned something similar this session

### Buying Intelligence
- 🎯 **Intent selector** — Switch between Resell / Keep / Gift to reframe the verdict
- 💰 **ROI calculator** — Full margin math against what you actually paid
- 🎨 **Color-tag sale bar** — Tap a tag color and all margin math updates automatically
- 💲 **Break-even calculator** — Max tag price to hit your target ROI
- 🚩 **Red flag detector** — Flags damage, fakes, or low sell-through risk
- 📦 **Shipping risk estimate** — Size/weight impact on your margin
- 🎁 **Lot & seasonal notes** — Bundle tips and timing signals

### Listing Tools
- 📝 **Platform listing drafts** — Tabbed view: eBay, Poshmark, Mercari, Facebook
- 💡 **Per-platform tips** — What to emphasize on each marketplace
- 🏆 **Best venue picker** — Recommends the right platform per item
- 📅 **Best day to list** — Category-specific timing recommendations
- ✅ **Cross-list checklist** — Everything to prep before posting

### Photo Tools
- 📷 **4-slot photo panel** — Main / Detail / Damage / Clean BG
- ⭐ **Photo quality scorer** — AI rates your shot 0-100 with improvement tips
- 🖼️ **Background analyzer** — Flags clutter before you list

### Session & P&L Tracking
- 🗂️ **Swipe review** — Keep / Pass / Maybe on your full scan history
- 💼 **Trip P&L** — Net profit per session with CSV export
- 📈 **Co-pilot panel** — Hit rate, avg ROI, top category, comp accuracy %
- 💾 **Persistent storage** — Scan history and P&L survive browser refreshes
- 📊 **True P&L panel** — Days-on-market tracker and sell-price confirmation log

---

## 🚀 Live Demo

👉 **[ohsusannamarie.github.io/thrift-scout](https://ohsusannamarie.github.io/thrift-scout)**
<!-- 
---

## 📱 Screenshots

| Scan & Appraise | Verdict Card | Live eBay Comps | Trip P&L |
|---|---|---|---|
| ![scan](screenshots/scan.png) | ![verdict](screenshots/verdict.png) | ![comps](screenshots/comps.png) | ![pl](screenshots/pl.png) |
-->
---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML/CSS/JS — single self-contained file |
| AI | Anthropic API (`claude-sonnet-4-6`) with vision |
| Live comps | `web_search_20250305` tool via Anthropic API |
| Storage | Browser localStorage |
| Fonts | Space Grotesk, Space Mono, Inter |
| Hosting | GitHub Pages |

---

## ⚙️ Setup

1. Clone the repo
```bash
   git clone https://github.com/ohsusannamarie/thrift-scout.git
```

2. Open `index.html` in your browser

---

## 📄 License

MIT — use freely, attribution appreciated.

---

## 🙏 Built With

- [Anthropic Claude](https://anthropic.com) — AI appraisal, vision analysis, and live comp search
- [GitHub Pages](https://pages.github.com) — Free hosting, no server required

---

*For everyone who has ever stood in a Goodwill aisle wondering if that thing is worth $4.99.*
