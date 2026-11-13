SUPRAAKASH FINANCE MANAGEMENT — V18 PWA PACKAGE

PACKAGE CONTENTS
- index.html: V18 Dynamic Year app, with PWA metadata added.
- manifest.webmanifest: install name, portrait display, and app icon declarations.
- sw.js: offline app-shell cache and update handling.
- icons/: updated SUPRAAKASH Finance Management launcher icon (192x192, 512x512) plus the full-resolution master icon.

IMPORTANT DATA SAFETY
1. Keep your existing V16/V18 HTML and backup file safe.
2. Before moving to the hosted PWA, export a fresh JSON backup from the currently working app.
3. A hosted PWA uses a different browser origin/storage area from a local content:// HTML file or another hosted app. Restore your JSON backup into the hosted PWA before relying on it.
4. Do not uninstall/delete the old app or its data until you have opened the hosted PWA, restored the backup, and verified Accounts, Income, Expenses, Savings, Goals, Portfolio, Settings, PIN, and Backup/Restore.
5. The service worker caches the app shell; financial records remain in the app's existing browser database/local storage, not in the cache.

GITHUB PAGES DEPLOYMENT
1. Create or open the GitHub repository you want to use for this app.
2. Upload the CONTENTS of this folder to the repository root (index.html, manifest.webmanifest, sw.js, and icons/).
3. In GitHub: Settings -> Pages -> Deploy from a branch -> select main and /(root), then Save.
4. Wait for the Pages deployment to finish. Open the published HTTPS address in Chrome on Android.
5. Test PIN, restore your JSON backup, and verify all modules and records.
6. In Chrome menu (three dots), choose "Install app" or "Add to Home screen".
7. Open the installed app and test it once online and once offline.

NOTE
This package is ready for HTTPS hosting. It has not been published to your GitHub account from this environment.
