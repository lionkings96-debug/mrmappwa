MrMAP — Updated PWA
===================

Includes:
- Home dashboard
- Fitness area with weight logging and target weight
- Weight progress graph and 7-day, 30-day, 3-month and 6-month views
- Body measurements: chest, waist, hip, butt, left/right arm, left/right forearm, left/right thigh
- Male outline illustration with measurement values displayed beside it
- Calendar with birthdays, anniversaries, holidays, meetings and personal events
- Notes, JSON backup export/import
- Dark black-and-gold mobile layout
- Offline cache via service worker

Publish on GitHub Pages:
1. Back up any existing MrMAP data using the app's More > Export backup.
2. Replace index.html, manifest.json, sw.js and README.txt in the repository with these versions.
3. Add icon.svg from this folder.
4. In GitHub, open Settings > Pages and ensure the main branch/root folder is published.
5. On iPhone, open the published site in Safari and refresh. If the old version remains, close MrMAP, reopen it online, and refresh again; the service worker cache is now v2.

Data compatibility:
The app continues using the localStorage key "mrmappwa". Existing weight entries may be retained. Because the old app used a different structure for some data, export a backup first and check entries after updating. The app does not sync data across devices.

Privacy:
This PWA stores entries in local browser storage, not encrypted. Export backups regularly. Scheduled alerts are not included; calendar events are displayed in-app.
ms.
- This starter has not been audited for security or medically/financially validated.
