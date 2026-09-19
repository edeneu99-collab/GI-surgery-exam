# GI Surgery Study Hub (PWA)

Files: `index.html` (the app), `manifest.webmanifest`, `sw.js` (offline cache), `icons/`, `.nojekyll`.

## Put it on GitHub Pages
1. Create a new repository on github.com (e.g. `gi-hub`, public).
2. Upload ALL files and the `icons` folder to the repository root (drag and drop in "Add file > Upload files"). Make sure `.nojekyll` is included.
3. Settings > Pages > Build and deployment: Source "Deploy from a branch", Branch `main`, folder `/ (root)`, Save.
4. After about a minute the site is at `https://YOUR-USERNAME.github.io/gi-hub/`.

## Install on your phone or laptop
- Android / Chrome: open the link, menu > Install app (or Add to Home screen).
- iPhone / Safari: open the link, Share > Add to Home Screen.
- Desktop Chrome / Edge: install icon in the address bar.
It then works offline.

## Your data
Edits, tags, ticks and the exam date are saved in the browser on that device only.
Use Export regularly (and Import to move data between devices, or from the Claude artifact version).

## Updating the hub
Replace `index.html` in the repository. Then change `VERSION` in `sw.js` (for example `gi-hub-v4`) so the phones fetch the new file. Open the app twice to see the update.
