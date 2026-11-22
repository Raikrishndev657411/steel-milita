# Steel Militia

A 3D tank / jet / warship battle game that runs in the browser (phone, tablet or desktop).

## Put it online with GitHub Pages (free)

1. **Unzip** this package on your device first. GitHub does not unzip files for you.
2. On github.com click **+ → New repository**. Give it a name (for example `steel-militia`), set it to **Public**, and create it.
3. On the new repository page click **uploading an existing file** (or **Add file → Upload files**).
4. Drag in **everything inside the unzipped folder**: `index.html`, `sw.js`, `manifest.webmanifest`, `README.md` and the whole `icons` folder. Click **Commit changes**.
5. Open **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
6. Wait about a minute. Your game is live at `https://YOUR-USERNAME.github.io/steel-militia/`.

## Install it like an app

- **iPhone / iPad (Safari):** Share button → **Add to Home Screen**.
- **Android (Chrome):** menu (⋮) → **Install app** / **Add to Home screen**.
- It opens full screen and keeps working offline after the first load.

## Good to know

- The 3D engine (three.js r128) loads from the cdnjs CDN on the first visit and is then cached for offline play.
- Saved progress (coins, vehicles, unlocks) is stored in the browser on each device.
- The online lobby only works inside Claude and is skipped on GitHub Pages. Everything else works.
- **Coupon codes** are in `index.html`. Search for `COUPON CODES` and edit the `COUPONS` list.
- **After you change `index.html`**, open `sw.js` and change `VERSION` (for example to `steel-militia-v2`) so phones pick up the update.
