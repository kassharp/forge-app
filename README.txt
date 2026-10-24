FORGE PWA package

Files: index.html, manifest.webmanifest, service-worker.js, icons/.

Host the contents of this folder on an HTTPS static host. Do not open index.html directly if you want installation/offline support.

DATA SAFETY: The app's Backup button now exports all localStorage keys as a full FORGE backup. On the existing version, tap Photos > Backup BEFORE moving to a hosted origin. The old version's previous Backup button exported only photos, check-ins, and workout history; it did not include all planner/nutrition keys. Because of that, use this package's full backup only after loading the updated version on the original storage origin, or keep the original app open and do not clear browser data. Restoring overwrites matching keys in the current app.
