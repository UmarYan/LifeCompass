LifeCompass PWA — Version 0.4 (Rebuilt on v0.2 base)
===================================================

This rebuild uses the v0.2 package as the starting base, retaining its PWA install support, manifest and app icons. The v0.4 assessment and review improvements are layered on top.

Features:
- Advanced assessment questionnaire and domain reflections
- Assessment-based smart priority suggestions
- Detailed life assessment report with print / Save as PDF
- Assessment review snapshot comparison
- Goal action-step progress tracking
- Improved responsive mobile dashboard
- Life Wheel, Deep Analysis / SWOT, 90-Day Plan, Review History
- Backup / Restore and CSV scorecard export
- App icons, install prompt and PWA support

Deploy:
1. Extract the ZIP.
2. Upload the folder contents to an HTTPS static host (GitHub Pages, Netlify, etc.).
3. Open the hosted URL in Chrome on Android and use Install App or Chrome menu > Install app / Add to Home screen.

Data:
Assessment information is stored in browser LocalStorage; there is no login/cloud sync. Export JSON backups regularly. This is a self-reflection tool, not a clinical or psychological diagnostic tool.

Validation:
JavaScript and service-worker syntax, manifest parsing, icon dimensions and ZIP integrity were checked. Browser/device install testing was not performed.


LifeCompass PWA v0.5 — Assessment UI update: horizontal scrollable domain tabs and contained vertical question/reflection pane with sticky Previous/Next controls.
