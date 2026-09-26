# LevelBook

A private study monitor for SSC JE and TNPSC AE preparation. Everything runs in
your browser — your plan, tracker, revision schedule, sleep log, and
comprehensive test scores are stored only on the device you open it on.

## Files in this folder
- `index.html` — the app. This is the only file you actually need to open.
- `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png` — let the
  site be installed to a phone's home screen and work offline once loaded.

## I could not push this for you
I don't have internet access from where I run, so I can't push to your GitHub
repository myself. Please add these 5 files yourself, using whichever of the
two options below is easier.

### Option A — upload from the browser (no computer needed)
1. Go to `https://github.com/heist3693-hub/Levelbook`.
2. Tap **Add file → Upload files**.
3. Upload all 5 files from this folder (`index.html`, `manifest.json`,
   `service-worker.js`, `icon-192.png`, `icon-512.png`).
4. Tap **Commit changes**.

### Option B — with git, from a computer
```
git clone https://github.com/heist3693-hub/Levelbook.git
cd Levelbook
# copy in index.html, manifest.json, service-worker.js, icon-192.png, icon-512.png
git add .
git commit -m "Add LevelBook study monitor"
git push
```

## Turn on GitHub Pages (one-time)
1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: `main` (or `master`), folder: `/ (root)`. Save.
4. After a minute or two, your site is live at:
   `https://heist3693-hub.github.io/Levelbook/`

## Important — moving your existing data
Right now your data lives inside whatever browser copy you've been using
(opened from a file on your phone). A page hosted at a new web address starts
with empty storage — that's just how browser storage works, tied to one
address.

To bring your existing plan, logs, and test scores across:
1. Open your current copy of LevelBook.
2. Go to **Settings → Save backup**. This downloads a `.json` file.
3. Open the new hosted site (`https://heist3693-hub.github.io/Levelbook/`).
4. Go to **Settings → Restore backup** and pick that `.json` file.

After that, keep using the hosted link going forward (bookmark it, or add it
to your home screen from that page) so everything stays in one place.
