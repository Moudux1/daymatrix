# DayMatrix PWA

## GitHub Pages
1. Upload every file in this folder to the root of a GitHub repository.
2. Open Settings > Pages. Choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
3. Open the published HTTPS URL in Safari. Use Share > Add to Home Screen.

## Storage and offline
- Data uses IndexedDB with a localStorage recovery copy where browser storage permits.
- The service worker caches the app shell after the first successful online visit, enabling offline app-shell launches.
- This is local-only storage, not cloud sync. Export JSON backups regularly. Clearing Safari website data can erase local records.
- Service-worker updates may take a short time to appear after publishing.
