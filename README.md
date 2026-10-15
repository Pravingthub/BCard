# Pravin's business card (installable app)

## Upload to GitHub, all of it
Upload **every file and the `icons` folder** to the root of your repository:

    index.html
    manifest.webmanifest
    sw.js
    icons/  (4 images)

Then go to Settings → Pages → Deploy from a branch → main, / (root) → Save.
Your card will be at `https://<username>.github.io/<repo>/`.

## Install on your phone
**iPhone (Safari):** open the link → Share → Add to Home Screen → Add.
**Android (Chrome):** open the link → tap the install icon at the top of the card, or ⋮ → Install app.

Tapping the "My Card" icon opens straight to the full-screen contact code, works without signal, and keeps the screen awake while it's showing.

## Updating details later
Edit `index.html`, then in `sw.js` change `pravin-card-v1` to `pravin-card-v2` so installed phones pick up the change.
