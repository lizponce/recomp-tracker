# Body Recomp Tracker

A personal body recomposition tracking app — fat loss, muscle retention, and visceral fat reduction — with an AI coach powered by Claude.

## Features
- **Dashboard** — InBody metrics, weekly averages, goal progress bars, body composition and calorie charts
- **Log today** — daily steps, calories, macros, sleep, water, workout type
- **InBody scan log** — track every scan with delta comparisons
- **History** — full log with color-coded badges
- **AI coach** — weekly review, macro check, plan adjustment, InBody analysis
- **Settings** — customize all goals and manage your API key

## Setup on GitHub Pages

1. Fork or create a new repo
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source: main branch / root**
4. Your app will be live at `https://yourusername.github.io/reponame`

## AI Coach Setup

The AI coach uses the Anthropic API directly from your browser.

1. Get a free API key at [console.anthropic.com](https://console.anthropic.com) → API Keys
2. Open the app → AI coach tab → paste your key
3. Your key is stored only in your browser's localStorage

> **Note:** Your API key is never sent anywhere except directly to `api.anthropic.com`. It is not stored on GitHub or any server.

## Data

All data is stored in your browser's `localStorage` — nothing is sent to any server. Clearing your browser data will erase your logs, so export periodically if needed.

Seed data covers May 22 – June 4, 2026 (weeks 1 and 2 of the program).
