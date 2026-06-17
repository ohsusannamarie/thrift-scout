# 🏷️ Thrift Scout

Scan any thrift find with your phone and know in seconds if it's worth buying — live eBay sold comps, full ROI math, and platform listing drafts, all in one shot.

![License](https://img.shields.io/badge/license-MIT-blue)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-222?logo=github)
![Built with Claude](https://img.shields.io/badge/built%20with-Claude%20Sonnet-blueviolet)

- 📸 Point your camera at any item and get a buy/pass verdict with live eBay sold comps in under 10 seconds
- 💰 Full margin math against the tag price you paid — ROI %, break-even max, and shipping risk before you commit
- 📝 Platform listing drafts for eBay, Poshmark, Mercari, and Facebook ready to copy the moment you decide to buy

---

## ✨ Features

### Core Appraisal
- 📸 **Camera scan** — Captures any item from your phone; reads condition, brand, and model from the photo
- 🤖 **AI appraisal** — Returns estimated retail value, resale range, and a 1-5 confidence rating
- 📊 **Live eBay comps** — Pulls real sold listings in real time, labeled LIVE or EST so you know the source
- 🏷️ **Swing-ticket verdict** — Delivers a Buy / Keep / Gift / Pass call in a scannable ticket UI
- 🔁 **Dupe detector** — Flags when you've already scanned something similar this session

### Buying Intelligence
- 🎯 **Intent selector** — Switch between Resell / Keep / Gift to reframe the verdict and math for your actual goal
- 💰 **ROI calculator** — Computes net margin against what you paid, accounting for fees and shipping
- 🎨 **Color-tag sale bar** — Tap a tag color and every margin number updates automatically for that discount
- 💲 **Break-even calculator** — Shows the max you can pay and still hit your target ROI
- 🚩 **Red flag detector** — Flags damage, fakes, missing parts, and low sell-through categories before you buy
- 📦 **Shipping risk estimate** — Estimates size and weight impact on your margin before you commit
- 🎁 **Lot & seasonal notes** — Suggests bundle opportunities and timing signals per item

### Listing Tools
- 📝 **Platform listing drafts** — Generates title, description, and price for eBay, Poshmark, Mercari, and Facebook in one tap
- 💡 **Per-platform tips** — Tells you what to emphasize on each marketplace for this specific item
- 🏆 **Best venue picker** — Recommends the single highest-ROI platform for each item
- 📅 **Best day to list** — Category-specific timing so your listing goes live when buyers are looking
- ✅ **Cross-list checklist** — Everything to prep before you post, so nothing gets missed

### Photo Tools
- 📷 **4-slot photo panel** — Dedicated slots for Main, Detail, Damage, and Clean Background shots
- ⭐ **Photo quality scorer** — Rates your shot 0-100 and tells you exactly what to fix
- 🖼️ **Background analyzer** — Flags clutter and distractions before your listing goes live

### Session & P&L Tracking
- 🗂️ **Swipe review** — Keep / Pass / Maybe on every scan from the session before you check out
- 💼 **Trip P&L** — Net profit per session with one-tap CSV export
- 📈 **Co-pilot panel** — Tracks your hit rate, avg ROI, top category, and comp accuracy over time
- 💾 **Persistent storage** — Scan history and P&L survive browser refreshes via localStorage
- 📊 **True P&L panel** — Days-on-market tracker and sell-price confirmation log to measure actual vs estimated comps

---

## 🚀 Live Demo

👉 **[ohsusannamarie.github.io/thrift-scout](https://ohsusannamarie.github.io/thrift-scout)**

---
<!--
## 📱 Screenshots

| Scan & Verdict | Live eBay Comps | Listing Drafts | Trip P&L |
|---|---|---|---|
| ![verdict](screenshots/verdict.png) | ![comps](screenshots/comps.png) | ![listing](screenshots/listing.png) | ![pl](screenshots/pl.png) |

---
-->
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

```bash
git clone https://github.com/ohsusannamarie/thrift-scout.git
```

Open `index.html` in your browser. No build step, no server, no dependencies.

---

## 📄 License

[MIT](LICENSE) — use freely, attribution appreciated.

---

## 🙏 Built With

- [Anthropic Claude](https://anthropic.com) — AI appraisal, vision analysis, and live comp search
- [GitHub Pages](https://pages.github.com) — Free hosting, no server required

---

*For everyone who has ever stood in a Goodwill aisle holding something weird, wondering if that thing is worth $4.99.*
