# RUNLAB – Half Marathon Command Center

A small, responsive German-language dashboard for tracking easy running and football sessions while preparing for a possible half marathon in July 2027.

## Deploy with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. After GitHub Pages finishes deploying, open the URL shown on that page.

## Files
- `index.html` – dashboard
- `manifest.webmanifest` – installable web-app metadata
- `sw.js` – basic offline cache
- `icon.svg` – app icon

## Notes
Training entries are stored locally in the browser (localStorage). There is no cloud sync, no real AI coach, and no automatic Pixel Watch/Fitbit/Health Connect integration. The check-in is a simple rule-based reminder, not medical advice. The dashboard deliberately treats football as training load and encourages recovery; discuss additional running and race eligibility with a parent, coach, and qualified healthcare professional.
