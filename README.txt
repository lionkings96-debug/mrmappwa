MrMAP — Personal Dashboard Upgrade
==================================

Included features:
- Existing black-and-gold PWA layout, fitness, weight graph and body measurements
- Calendar and special-day events
- Notes with category, search and pin/unpin
- Reminders with date, time, repeat preference, and done/undo tracking
- My Day daily journal with mood and notes
- Insights with weight history and monthly counts
- JSON backup and restore
- Offline cache via service worker

IMPORTANT — CLOUD SYNC IS NOT ENABLED YET
This package still stores data in localStorage on each browser/device. It does NOT yet synchronise between iPhone and Windows. Enabling secure cloud sync requires configuring a cloud project (for example Supabase), authentication, database tables and row-level security. No secrets or credentials are included in this package.

IMPORTANT — REMINDERS
Reminder entries are stored and displayed inside MrMAP. Browser background notifications are not implemented in this version, and repeat values are stored as preferences but do not automatically create new occurrences.

Upgrade / publish on GitHub Pages:
1. Export a JSON backup from your current MrMAP before replacing any files.
2. Unzip this package and replace the repository's index.html, manifest.json, sw.js, README.txt and icon.svg with these files.
3. Commit/publish to the same GitHub Pages repository and path as the existing app.
4. Open the website online and refresh MrMAP. If an old cached screen persists, close it and reopen the site.
5. Check your fitness and calendar records, then use Import backup only if needed. Do not import an older backup over newer data unless you intend to replace it.

Data compatibility:
The app retains localStorage key "mrmappwa" and adds reminders and daily journal arrays. Existing local records should remain in that browser, but always export a backup before updating. iPhone and Windows browser storage remain separate until cloud sync is configured.

Privacy:
Data is stored locally in the browser and is not encrypted by this app. Export backups regularly and protect the devices you use.
