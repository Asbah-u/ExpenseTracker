# 💸 Expense Tracker

A clean, responsive expense tracking web app built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just open `index.html` in a browser and start tracking!

## ✨ Features

- Add expenses with description, amount, category, and date
- 7 categories: Food, Transport, Shopping, Health, Bills, Entertainment, Other
- Dashboard with total spent, this month's spending, transaction count, and average
- Visual bar chart of spending by category
- Recent entries panel
- Filter expenses by category
- Delete any entry
- Dark mode support (auto-detects system preference)
- Data saved in browser's `localStorage` — persists across sessions

## 🚀 Getting Started

### Run locally
Just open `index.html` in any browser — no setup needed!

### Deploy on GitHub Pages
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/expense-tracker`

## 🛠️ Customization Ideas

- Change currency symbol (`₹`) to your own (e.g. `$`, `€`) — search and replace in `index.html`
- Add new categories in the `<select>` dropdowns and `catColors`/`emojis` objects
- Add a monthly budget limit with a progress bar
- Add CSV export with `Blob` and `URL.createObjectURL`
- Connect to a backend (Firebase, Supabase) for multi-device sync

## 📁 Project Structure

```
expense-tracker/
└── index.html    ← entire app (HTML + CSS + JS in one file)
└── README.md     ← this file
```

## 🧰 Tech Stack

- HTML5
- CSS3 (CSS Variables, Grid, Flexbox, dark mode via `prefers-color-scheme`)
- Vanilla JavaScript
- localStorage for persistence
- [Tabler Icons](https://tabler-icons.io/) (CDN)

## 📄 License

MIT — free to use, modify, and share.
