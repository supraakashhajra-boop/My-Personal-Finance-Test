MY PERSONAL FINANCE — FINAL CANDIDATE (Preview + Restore integration fix)

Files: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, README.txt

This candidate fixes the JSON backup preview scope issue and connects the restore
handler to the app's data/state functions. It also allows Settings handlers to be
re-attached when the Settings view is opened again.

IMPORTANT:
- Deploy only to the separate My-Personal-Finance-Test repository first.
- Do not replace the original V1.9 live repository until the test-site restore,
  record counts, refresh persistence, and PWA checks have passed.
- Preview is read-only. Apply Restore replaces records in the TEST site's own
  browser-origin database after creating a safety snapshot.
- Browser notification delivery in the background is not guaranteed.
