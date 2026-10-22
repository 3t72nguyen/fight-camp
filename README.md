# Fight Camp Timer

A 5-day boxing circuit timer for iPhone. Voice rep countdown, rest timer, set / rest / plank wheels,
scrolling now-and-next bar, and a session checklist. Runs full-screen from the home screen and works offline.

## Put it on your iPhone

The app has to be served over HTTPS once so Safari can install it. GitHub Pages does this for free.

### Host on GitHub Pages
1. On github.com, create a new **public** repository (for example `fight-camp`).
2. Click **Add file > Upload files**, drag in everything from this folder (including the `icons` folder, `.nojekyll`, `sw.js`, `manifest.webmanifest`, `index.html`), then **Commit**.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/fight-camp/`.

### Install on the iPhone
1. Open that address in **Safari** (it must be Safari, not Chrome).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open it once while online so the fonts and files are saved. After that it works offline.

## Notes
- Tap the pencil beside any exercise in the Session list to set its own reps (1 to 100) or seconds (5 to 300). Edits are saved on the phone, and Reset edits puts the plan back.
- Settings (sets, rest, plank time, pace, voice) are saved on the phone. The home-screen app keeps its own copy, separate from Safari.
- The Sound button turns the coach voice and the rest-time tick on or off. The tick goes quiet while the coach speaks and comes back afterwards.
- The coach uses the best English voice on the phone. For a more natural sound, download an Enhanced voice in Settings > Accessibility > Spoken Content > Voices > English (Australia or UK).
- Sound starts after your first tap. Keep the ring/silent switch off silent and turn the volume up.
- The screen stays awake during a workout on iOS 16.4 and later.
- To publish an update, replace the files in the repo and raise `VERSION` in `sw.js` (for example `fight-camp-v5`).
- Any other static host with HTTPS works too (Netlify Drop, Cloudflare Pages).
