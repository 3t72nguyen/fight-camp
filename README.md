# Fight Camp Timer

A 5-day boxing circuit timer for iPhone: voice rep countdown, rest timer with tick, set / rest / plank / pace wheels,
a scrolling now-and-next tape and a session checklist. It runs full screen from the home screen and works offline.
Every file is in one flat folder (no subfolders), so it uploads to GitHub straight from an iPhone.

## Put it on GitHub Pages
1. Unzip the download. In the Files app, tap the zip once and a folder appears.
2. On github.com (Safari), open your repository. If you uploaded an older copy, you can leave it. The new files replace files with the same names.
3. Tap **Add file > Upload files > choose your files**, select **all 9 files** from the folder, then **Commit changes**.
4. Open **Settings > Pages**, set **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**. After a minute the app is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

Files that must all be in the repository root: `index.html`, `manifest.webmanifest`, `sw.js`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `splash-1284x2778.png`, `README.md`.

## Install on the iPhone
1. Open the address in **Safari** (it must be Safari).
2. Tap **Share > Add to Home Screen > Add**.
3. Open it once while online. After that it works offline.

If you installed an older copy, delete its home-screen icon first, then add it again so the new version and icon are used.

## Notes
- Settings, edited reps and the chosen day are saved on the phone.
- The Sound button turns the coach voice and the rest tick on or off. Keep the ring/silent switch off silent.
- For a more natural coach voice, download an Enhanced English voice in Settings > Accessibility > Spoken Content > Voices.
- To publish an update later, replace the files and raise `VERSION` in `sw.js`.
