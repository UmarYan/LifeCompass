LifeCompass PWA — First working build

Files:
- index.html: app UI + assessment and storage logic
- manifest.json: install metadata
- sw.js: basic offline cache

Run locally:
Open index.html in a modern browser. LocalStorage persistence works. PWA installation and service worker offline cache require serving over HTTPS or localhost (e.g. GitHub Pages).

Features:
- 15 life domains, 75 self-rating questions (1–10)
- Domain reflections, overview scorecard, Life Wheel visualization
- SWOT + root cause + Continue/Improve/Stop/Start analysis
- 90-day plan, max 3 recommended priorities, action steps, weekly check-in
- Review snapshots, JSON backup/restore, CSV score export
- Bengali UI, responsive mobile layout

Privacy:
Data remains in this browser's LocalStorage. Clearing browser site data may remove it. Export a JSON backup regularly. No login or cloud sync.

Note: This is a self-reflection tool, not a clinical diagnostic instrument.
