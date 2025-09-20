# GolfFit (preloaded)

Simple, no-fuss training app for golf strength & mobility. Runs in the browser and can be added to your phone as an app.

**Live site:** https://forethewin.github.io/golfit/

## Install on your phone
**iPhone (Safari)**
1. Open the live link above.
2. Tap **Share** → **Add to Home Screen**.
3. Launch GolfFit from your home screen.

**Android (Chrome)**
1. Open the live link above.
2. Tap the **⋮** menu → **Add to Home screen**.
3. Launch GolfFit from your home screen.

## Repo contents
- `index.html` – the entire app in a single file (preloaded plan, strict day progression).
- `apple-touch-icon.png` – iOS home screen icon (180×180).
- `icon-192.png`, `icon-384.png`, `icon-512.png` – Android/desktop icons.

## Updating the site
1. Upload a new `index.html` to the repo root (replace the existing file).
2. Commit changes.
3. Wait 1–2 minutes for GitHub Pages to redeploy, then refresh the site.
   - If you see an old version, add `?v=2` to the URL to bust cache.

## Changing the icon
Replace the PNG files in the repo with your own (same filenames/sizes):
- `apple-touch-icon.png` (180×180)
- `icon-192.png`, `icon-384.png`, `icon-512.png`

Make sure these lines are present inside `<head>` in `index.html`:

```html
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="192x192" href="/icon-192.png">
<link rel="icon" type="image/png" sizes="384x384" href="/icon-384.png">
<link rel="icon" type="image/png" sizes="512x512" href="/icon-512.png">
```

Then commit the changes and refresh your site.
