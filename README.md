# CaffiNote ☕ – Daily Caffeine Tracker 
Hackaton Prototype - submission for Girls Hoo Hacks Hackathon 2025


**Live demo:** https://an9o.github.io/CaffiNote/

CaffiNote is a single-file, frontend-only web app that lets you:
- Set a profile and a daily caffeine limit rule (Auto / Fixed / per kg / Custom)
- Log drinks by volume; built-in database for common beverages
- See daily totals vs limit and a monthly “dot map” heat view
- Export/Import your data (JSON). All data stays in your browser (localStorage).

**Prototype thresholds (not medical advice):**
- Auto: ≥18 → 400 mg/day; 12–17 → 100 mg/day; <12 → 0 mg/day
- You can override with Custom or 3 mg/kg

## How to run locally
Open `index.html` in your browser, or host via GitHub Pages.

## What’s next (future work)
- Barcode scan / product DB
- Unit-aware recipes (espresso shots, mixed drinks)
- PWA install + notifications when nearing limit
- Simple account sync / multi-device
- Accessibility & internationalization
