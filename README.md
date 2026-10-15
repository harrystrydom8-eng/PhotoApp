# Site Photo Organiser

Sort site photos by job and date, name each photo, and save tidy ZIP folders or PDF photo reports.
Everything runs in the browser: photos never leave the device.

## Put it online with GitHub Pages

1. Sign in at https://github.com (create a free account if needed).
2. Click **+** (top right) > **New repository**.
   - Name: `site-photo-organiser`
   - Visibility: **Public** (required for free GitHub Pages)
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Drag in everything **inside** this folder (index.html, sw.js, manifest.webmanifest, README.md and the
   fonts, icons and vendor folders). `index.html` must be at the top level, not inside another folder.
5. Click **Commit changes**.
6. Go to **Settings** > **Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**,
   Branch to **main** and folder **/ (root)**, then click **Save**.
7. Wait 1 to 2 minutes and refresh the Pages screen. Your link appears at the top:
   `https://YOUR-USERNAME.github.io/site-photo-organiser/`

## Install it

- **Android (Chrome):** open the link, then tap **Install app** in the app, or the menu (three dots) > **Install app**.
- **iPhone / iPad (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Windows / Mac (Chrome or Edge):** open the link and click **Install app** in the app, or the install icon in the address bar.

Once installed it opens like a normal app and works without signal on site.

## Updating

Upload the new `index.html` to the repository (Add file > Upload files) and commit. Installed copies pick up the
change the next time they're opened with internet. If you ever replace files in `fonts`, `vendor` or `icons`,
also change `VERSION` in `sw.js` (for example to "v2").

## Notes

- The repository is public, so anyone can see the app's code. Your photos are never uploaded anywhere.
- Places from photo GPS show as coordinates in this version.
