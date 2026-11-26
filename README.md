# RUNLAB V2.0 – Personal Performance OS

RUNLAB is a German-language, mobile-first running and activity dashboard designed to keep running, football, recovery and personal notes together.

## V2.0 highlights
- Redesigned performance dashboard with daily briefing and live summaries from locally stored activity data.
- Existing training, calendar, statistics, journal, GPS, recovery, coach and notification areas retained.
- Full local-data backup and merge-based restore for supported RUNLAB data groups.
- Updated visual system, app identity, responsive layout and service-worker cache version.

## Deploy with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After GitHub Pages finishes deploying, open the URL shown on that page.

## Files
- `index.html` – application and interface
- `manifest.webmanifest` – installable web-app metadata
- `sw.js` – network-first page loading and offline fallback cache
- `icon.svg` – RUNLAB app icon

## Data and privacy
Training entries, journal notes, preferences, routes and recovery check-ins are stored locally in the browser. They are not automatically synced to a cloud account. Use **Settings → Data Vault** to export a complete backup and to merge a backup into the current browser data. Do not clear browser/site storage unless you have exported a backup first.

RUNLAB does not provide medical advice, automatic wearable synchronization or a real AI coach. GPS depends on browser location permissions and may pause when the app is in the background. Training suggestions are informational; recovery and wellbeing take priority.
