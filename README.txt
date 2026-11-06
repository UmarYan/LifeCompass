LifeCompass PWA — Version 0.2
=============================

v0.2 enhancements:
- Custom LifeCompass app icon (192px and 512px PNG, scalable SVG, Apple touch icon)
- Manifest icons with maskable icon support for Android launchers
- Install App button and browser install prompt integration
- Updated service worker cache version and cache cleanup
- Apple mobile web app metadata
- Retains v0.1 assessment data model and features

Deploy:
1. Extract the ZIP.
2. Upload the contents of LifeCompass_PWA_v0.2 folder to an HTTPS static host (GitHub Pages, Netlify, etc).
3. Open the hosted URL in Chrome on Android.
4. Use Install App button if the browser prompt appears. If not, Chrome menu (⋮) > Install app / Add to Home screen.
5. Launch from home screen.

PWA install requirements:
- HTTPS or localhost
- valid manifest and registered service worker
- browser installability conditions may vary by browser/version

Data:
All assessment data remains in browser LocalStorage; there is no login/cloud sync.
Export JSON backup regularly. This is a self-reflection tool, not a diagnostic tool.
