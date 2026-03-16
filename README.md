# 🎾 Big NC Tennis — Scheduling & Roster App

A full-featured tennis academy management system for **Big NC Tennis**.

## What It Does

- **Student & Coach Dashboards** — book sessions, track progress, message coaches
- **Live Booking System** — calendar-based scheduling with real-time coach availability
- **Roster Manager** — seasonal enrollment, attendance tracking, package management
- **Auto-Schedule Engine** — AI-powered coach↔student matching (100-point formula)
- **Email & Calendar Export** — Google Calendar, Outlook, .ics, and email drafts
- **Drill Library** — 17 drills with YouTube links, assignable by coach
- **Season Management** — create, archive, and roll over seasons with one click

## Live App

🌐 [bignctennis.github.io/bignctennis](https://bignctennis.github.io/bignctennis)

## Files

| File | Description |
|------|-------------|
| `index.html` | Main student & coach app |
| `roster.html` | Roster & season management dashboard |
| `test-suite.html` | Automated test suite (57 tests) |
| `data.js` | Shared data, logic, and formulas |

## Setup

1. Clone or download this repository
2. Create a [Supabase](https://supabase.com) project
3. Run `supabase_schema.sql` in the Supabase SQL editor
4. In `index.html`, replace:
```js
   const SUPABASE_URL = 'https://YOUR_PROJECT.supabase.co';
   const SUPABASE_ANON_KEY = 'YOUR_ANON_KEY';
   const DEMO_MODE = false;
```
5. Push to GitHub and enable GitHub Pages

## Demo Login

- **Student:** `student@demo.com` / `demo1234`
- **Coach:** `coach@demo.com` / `demo1234`

## Built With

- Vanilla HTML, CSS, JavaScript — no frameworks, no build tools
- [Supabase](https://supabase.com) for database and authentication
- Google Fonts (Bebas Neue + DM Sans)

## License

Copyright © 2026 Big NC Tennis. All rights reserved.
```

---

## 4. `CNAME` (Only if you have a custom domain)

If you want the app to live at `app.bignctennis.com` instead of `username.github.io/bignctennis`, create a file called exactly `CNAME` with one line:
```
app.bignctennis.com
