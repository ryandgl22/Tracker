WINTER FITNESS TRACKER — REBUILD V5

This is a real interface rebuild, not a mockup/CSS patch.

WHAT CHANGED
- Removed the phone-first/laptop-analysis wording.
- New road-bike + weights identity in the real header.
- Editable Goals card directly on the Dashboard/Home screen.
- Goals are saved locally and included in V5 JSON backups.
- New visual Dashboard, consistency cards and real-data charts.
- Reworked Analysis for weight, nutrition, strength and cycling.
- Existing winterFitness.v3 entries remain compatible.

UPDATE
1. FIRST export a full backup from your current live tracker.
2. Unzip this package.
3. In the GitHub Tracker repository, upload/replace:
   index.html
   manifest.webmanifest
   service-worker.js
   icon-192.png
   icon-512.png
4. Commit the changes.
5. Wait for GitHub Pages deployment.
6. Refresh the site in Safari. The service worker in V5 is designed to fetch the newest version first.

Your existing GitHub Pages URL stays the same.
