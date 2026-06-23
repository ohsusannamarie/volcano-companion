# 🌋 Volcano Companion

**Know your dial. Know your session. Know the weird science behind it all.**

Your vaporizer's built-in dial tells you nothing — this app tells you everything: what's actually happening at each temperature zone, which terpenes you're chasing, and 200 facts that range from genuinely useful to deeply unhinged.

![License](https://img.shields.io/badge/license-MIT-blue)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-222?logo=github)
![No Install](https://img.shields.io/badge/no%20install-just%20open-brightgreen)

- 🎛️ **Dial Guide with live SVG visualizer** — color-coded zones from Too Cold (1-3) through Combustion Territory (7.5-9), with compound boiling points and zone-by-zone breakdowns
- 🔬 **Terpene + cannabinoid science table** — 9 compounds, exact boiling temps in °C and °F, what each one does, and which dial setting approximates it
- 🏆 **21 achievements across 6 series** — Core, Frog, Alien, Mushroom, Volcano, and Secret — with hidden easter eggs that reward exploration

---

## Features

### 🎛️ Dial Guide
- SVG dial visualizer that fills to zone midpoint with color matching the zone
- 6 temperature zones: Too Cold → Light & Flavorful → Flavor+Effect → Sweet Spot → Maximum Extraction → Combustion Territory
- Zone descriptions cover experience, effects, what you're releasing, and what to expect
- `dakotaApproved` flag on zone 6.5-7.5 for the true believers
- Collapsible terpene/cannabinoid science table — 9 compounds with boil temps and dial approximations
- 5-question FAQ section, also collapsible

### 🌿 Session Tab
- Session tracking and daily nudges (100 unique)
- 100 loading messages, 50 completion messages
- Live session state with achievement progress

### 📚 The Vault
- 200 categorized weird facts across 9 categories
- Fact #100 is a message. You'll know it when you see it.
- Fact #182 features Harvey, a goldendoodle. Do not skip it.

### 🏆 Achievements
- 21 achievements across 6 series (Core / Frog / Alien / Mushroom / Volcano / Secret)
- Easter eggs: tap the logo 7 times, hit zone 6.5-7.5, type `daNggg`
- Achievement unlock animations and persistent progress

---

## Live Demo

[https://ohsusannamarie.github.io/volcano-companion](https://ohsusannamarie.github.io/volcano-companion)

---
<!--
## Screenshots

| | |
|---|---|
| ![Dial Guide](screenshots/dial-guide.png) | ![Session Tab](screenshots/session.png) |
| *Dial Guide — SVG visualizer + zone breakdown* | *Session Tab — daily nudges and progress* |
| ![The Vault](screenshots/vault.png) | ![Achievements](screenshots/achievements.png) |
| *The Vault — 200 categorized facts* | *Achievements — 21 unlockables across 6 series* |

---
-->
## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | React + TypeScript |
| Build | Vite (bundled to single HTML) |
| Styling | Tailwind CSS + shadcn/ui |
| Data | Static JSON (data.ts) |
| Hosting | GitHub Pages |

---

## Setup

```bash
git clone https://github.com/ohsusannamarie/volcano-companion.git
cd volcano-companion
```

Open `index.html` directly in any browser — no server needed.

To rebuild from source:
```bash
npm install
npx vite build
# then run the bundle script to produce single-file HTML
```

---

## License

[MIT](LICENSE) — use freely, attribution appreciated.

To add the LICENSE file: during GitHub repo creation, select **MIT** from the license picker dropdown. GitHub will auto-generate it and the license badge will appear on your repo homepage automatically.

---

## Built With

- [React](https://react.dev) + [TypeScript](https://www.typescriptlang.org)
- [Vite](https://vitejs.dev)
- [Tailwind CSS](https://tailwindcss.com)
- [shadcn/ui](https://ui.shadcn.com)

---

*For everyone who has stood in front of a dial and thought: there has to be more to this than guessing.*
