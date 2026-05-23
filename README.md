<div align="center">

# 🌱 New Life
### Your AI-powered wellness & productivity companion

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶_Try_Now-ff8c42?style=for-the-badge)](https://khanishk6619-cmyk.github.io/new-life-app/)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Claude AI](https://img.shields.io/badge/Claude-AI_Powered-8B5CF6?style=for-the-badge)](https://anthropic.com)
[![No Build Step](https://img.shields.io/badge/No_Build_Step-Zero_Setup-4ECB8D?style=for-the-badge)](#-quick-start)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

A beautifully designed, **single-file** wellness app that runs entirely in the browser.  
No Node.js. No bundler. No installation. Just open and go.

**[✨ Try the Live Demo →](https://khanishk6619-cmyk.github.io/new-life-app/)**

</div>

---

## 📸 What It Looks Like

| Home Dashboard | Journal + AI | Workout Logger | Sleep Tracker |
|:-:|:-:|:-:|:-:|
| Life Score ring, streak, calories & water at a glance | Write reflections, log gratitude, get Claude AI pattern insights | 8 workout types, duration slider, weekly stats | Sleep score ring, moon quality rater, 7-night chart |

---

## ✨ Features

### 🏠 Home Dashboard
- **Life Score** (0–100) calculated live from mood, sleep, tasks, stress & water
- Streak tracker with grace days and milestone progress bar
- Quick-glance calories, water intake, and task completion

### 🎙️ AI Assistant (Claude-powered)
- Conversational daily check-ins with mood + energy tracking
- Personalized coaching and reflections
- Graceful offline fallbacks — works without an API key

### 💚 Health Center
- **4-7-8 breathing exercise** with animated expanding orb
- Stress tracker (1–10 slider) with 7-day bar chart
- Nutrition dashboard with macro breakdown

### 📓 Journal
- Daily reflections with 5-emotion mood picker
- 3-item gratitude list with contextual prompts
- **AI Pattern Insights** — Claude reads your entries and surfaces real mood trends
- Entry history with inline mood visualization

### 🏋️ Workout Logger
- **8 types:** Run, Lift, Yoga, HIIT, Swim, Cycle, Walk, Other
- Duration slider (5 min → 2 hrs) + Easy / Medium / Hard intensity
- Live calorie burn estimate before you log
- Session history + weekly activity chart with 150-min goal progress

### 🌙 Sleep Tracker
- **Sleep Score ring** (0–100) from duration × quality
- Bedtime / wake time pickers with live duration calc
- 5-moon quality rating — logs are blocked until rated
- 7-night history chart + **sleep debt** calculation

### ⚡ Productivity
- Task list with **Eisenhower priority matrix** (Do Now / Schedule / Delegate / Drop)
- Habit tracker with 30-day heatmap
- **Pomodoro focus timer** with circular SVG progress ring

### 📈 Progress
- Before vs. Now comparison (Day 1 → Today)
- 7-day Life Score trend chart
- AI-generated monthly insights panel
- Vision Board for goals

### 🤝 Community
- Friends leaderboard with streak counts
- Social feed (celebrations only — no comparisons, no pressure)
- Group wellness challenges with live participation counters

### 🏆 Achievements
- 8 achievements including **3 secret ones** discovered through use
- Confetti animation on unlock
- Motivational quotes per achievement

### ➕ Quick-Add FAB
- One-tap: **Water +1**, Log Mood, Add Task, Log Meal
- Floating action button above tab bar with blur backdrop

---

## 🚀 Quick Start

**Option 1 — Live demo (no setup):**  
👉 [khanishk6619-cmyk.github.io/new-life-app](https://khanishk6619-cmyk.github.io/new-life-app/)

**Option 2 — Run locally:**
```bash
git clone https://github.com/khanishk6619-cmyk/new-life-app.git
cd new-life-app

# macOS
open new_life.html

# Windows
start new_life.html

# Linux
xdg-open new_life.html
```

That's it. No `npm install`. No build step. No environment setup.

### ⚡ Enable AI Features (optional)

AI features work without a key (fallback responses are built-in), but for live Claude responses:

1. Get a free API key at **[console.anthropic.com](https://console.anthropic.com)**
2. Open `new_life.html` in any text editor
3. Find line ~20: `const ANTHROPIC_API_KEY = "";`
4. Paste your key: `const ANTHROPIC_API_KEY = "sk-ant-...";`
5. Save and reload — AI features activate instantly

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| UI Framework | **React 18** (CDN — no npm) |
| JSX Compiler | **Babel Standalone** (in-browser) |
| AI | **Anthropic Claude** (`claude-sonnet-4-6`) |
| Fonts | **Syne + DM Sans** (Google Fonts) |
| Styling | Pure CSS-in-JS (no external library) |
| Deployment | **GitHub Pages** |
| Bundle | **Single HTML file** (~160 KB) |

---

## 📱 Mobile-First Design

Built for phones first — 430px max-width, fixed tab bar, touch-friendly tap targets, smooth animations. Install it to your home screen via your browser's **"Add to Home Screen"** option for a native-app feel.

---

## 🗺️ Roadmap

- [ ] LocalStorage / IndexedDB persistence (survive refresh)
- [ ] PWA offline support with Service Worker
- [ ] Dark / Light theme toggle
- [ ] Export journal as PDF
- [ ] AI-generated workout plans
- [ ] Supplement & medication tracker
- [ ] Push notification reminders
- [ ] Data export (JSON / CSV)

---

## 🤝 Contributing

PRs are welcome! This is intentionally a **single-file app** — all changes live in `new_life.html`.

1. Fork the repo
2. Edit `new_life.html`
3. Open a PR with a clear description of what you added or fixed

For bigger features, open an issue first so we can discuss the approach.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<div align="center">

Built with ❤️ using [React](https://react.dev) and [Claude AI](https://anthropic.com)

**⭐ Star this repo if it helped you — it means the world!**

[Live Demo](https://khanishk6619-cmyk.github.io/new-life-app/) · [Report a Bug](https://github.com/khanishk6619-cmyk/new-life-app/issues) · [Request a Feature](https://github.com/khanishk6619-cmyk/new-life-app/issues)

</div>
