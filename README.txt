MrMAP — Personal Command Center (PWA)
=====================================

WHAT'S INCLUDED
- Home dashboard
- Tasks with date, time, priority, completion
- Weight log and target weight
- Custom workout checklist
- Personal events / meetings
- Notes and quick note
- Yearly, monthly and long-term goals with progress tracking
- Local JSON backup export/import
- Black-and-gold responsive layout
- Offline cache after first successful load

PRIVACY
This starter stores data in this browser on the iPhone using localStorage. It does not create an account or intentionally send your entries to a server. Browser storage is not encrypted, and iOS/Safari can clear website data. Export backups regularly. Anyone with access to the unlocked phone/browser may be able to view the data.

IMPORTANT ABOUT REMINDERS
The app can show browser notifications for reminders while it is open and running. iOS does not reliably run a web app in the background to fire scheduled reminders offline. Web Push on iPhone requires an installed Home Screen web app plus a push server and additional setup. For important reminders, also add them to Apple Calendar or Apple Reminders.

HOW TO PUT IT ON YOUR IPHONE (WINDOWS PC ONLY)
You need to publish the folder to an HTTPS website first. An easy free route is GitHub Pages:

1. On your Windows computer, create/sign in to a GitHub account.
2. Create a new public repository named mrmappwa (or any name).
3. Upload index.html, manifest.json, sw.js, icon.svg, and README.txt from this folder.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch", select the main branch and root folder, then Save.
6. Wait for GitHub Pages to publish. The HTTPS site URL will look like https://YOUR-USERNAME.github.io/mrmappwa/ .
7. On your iPhone, open that HTTPS URL in Safari.
8. Tap Share, then "Add to Home Screen", and tap Add.
9. Launch MrMAP from the new Home Screen icon. Open it once while online so it can cache files for offline use.

Keep the repository public only if you are comfortable sharing the app's code. Your personal entries are stored locally on your iPhone and are not committed to the repository. Do not add personal data to the website files.

HOW TO USE
- Add tasks, events, goals, notes, and exercises.
- Export a JSON backup from Privacy & Settings before clearing Safari website data or changing phones.
- To restore, open Privacy & Settings > Import backup.

LIMITATIONS
- This is a PWA, not a native App Store app.
- No iCloud sync, account, server-side database, or automatic backup.
- Notifications are best-effort while the app is open; they are not dependable background alarms.
- This starter has not been audited for security or medically/financially validated.
