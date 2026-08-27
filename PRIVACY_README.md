# My Life OS 3.1 — Local Privacy

## Privacy model
- Personal records are stored by the browser on the current device/origin.
- The app contains no cloud sync or upload feature.
- A Content-Security-Policy sets `connect-src 'none'`, blocking fetch/XHR/WebSocket-style external data connections from this app.
- User-selected photos/receipts stay in browser-side app data; they are not created as repository files.
- Backup export is manual and uses the suffix `.backup.json`.

## GitHub upload rule
Upload only the app package files. Never upload exported `.backup.json` files or private photos.

`.gitignore` blocks common private folders and backup/export filename patterns when using Git locally.

## Important
Browser storage can still be removed by the user/browser. Keep periodic offline backups somewhere private.
