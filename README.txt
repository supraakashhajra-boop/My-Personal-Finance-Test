MY PERSONAL FINANCE V2.0.5 — JSON RESTORE PREVIEW FIX

Fixes the non-working Verified Backup Preview: the Settings screen now has a JSON file picker, parses the user's selected backup, validates all expected tables, and displays file name, export date, version, per-table counts and financial summary without changing records. Apply is enabled only after a valid preview; before applying, it creates a separate IndexedDB safety snapshot and verifies table counts after restore. Footer/app version labels updated.

Upload all six files to the existing My-Personal-Finance-Test repository root and commit. Do not replace the live My-Personal-Finance V1.9 repository until all tests pass. Keep the downloaded JSON backup safe. Test restore only on the test website.
