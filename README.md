# Best Life Tracker

A PWA for tracking daily routines, hydration, sleep, and project work hours.

## Files

- `index.html` — Main app
- `service-worker.js` — Offline support
- `manifest.json` — PWA settings

## Upload to Cloudflare Pages

1. Go to https://dash.cloudflare.com
2. Click **Pages** → **Create a project** → **Direct upload**
3. Drag and drop all files OR select them from your device
4. Click **Deploy site**

That's it. Data is stored in localStorage and persists.

## Using the App

- **Settings** (top): Set wake time, bedtime, date
- **Routine** tab: Daily schedule with trackers
- **Tracking** tab: Weekly/monthly/annual stats
- **Projects** tab: Timer for BNBS, DEV, CAREER, IREC (editable H/M/S)
- **Workouts** tab: Track A/B/C components

### Data

- Export/Import buttons let you backup/restore to JSON
- localStorage is separate per domain

### Changes

Edit any input field. Timer pauses for 5 seconds after last edit.
