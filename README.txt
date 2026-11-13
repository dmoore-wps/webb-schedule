WEBB: WHERE IS EVERYONE?

Files in this folder:
- index.html: the schedule app
- manifest.webmanifest: Home Screen app metadata
- sw.js: offline cache service worker
- apple-touch-icon.png: iPhone Home Screen icon
- icon-192.png / icon-512.png: install icons
- favicon.svg: browser tab icon

Deployment target: GitHub Pages (HTTPS required for service workers).
Upload the CONTENTS of this folder to the root of the public webb-schedule repository.
Then enable GitHub Pages from Settings > Pages > Deploy from a branch > main > /(root).

After the site is published, open its HTTPS URL in Safari on the iPhone, let it load once while online, then use Share > Add to Home Screen. Open it once more while online so the offline cache can finish. Test in Airplane Mode afterward.

Important schedule limitations:
- This is based on Webb Building Schedule 2026-2027, Instructional Blocks.
- It identifies weekends, but it does not contain a school holiday/closure calendar.
- The source gives weekday-specific labels for Monday, Tuesday, and Thursday; Wednesday/Friday details are not specified.
- Where the source schedule leaves gaps, the app reports "Between scheduled blocks" rather than inventing an activity.
