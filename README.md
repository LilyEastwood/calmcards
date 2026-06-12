# Calm Cards

A simple, offline-friendly web app for picking calming activities. Open it in a browser or add it to your home screen like an app.

## Live site (GitHub Pages)

After enabling Pages (see below), the app will be at:

**https://YOUR-GITHUB-USERNAME.github.io/calmcards/**

Replace `YOUR-GITHUB-USERNAME` with your GitHub username. If you name the repo something other than `calmcards`, use that name in the URL instead.

## Enable GitHub Pages

1. Push this repo to GitHub (create a new repository named `calmcards`).
2. On GitHub, open the repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and folder to **/ (root)** → **Save**.
5. Wait a minute or two — GitHub will show the live URL at the top of the Pages settings.

## Add to home screen

- **iPhone:** Open the live link in Safari → Share → **Add to Home Screen**
- **Android:** Open in Chrome → menu → **Add to Home screen**

## Editing the app

Most content lives in `index.html`:

- **Activities** — the `activities` object near the top of the `<script>` block
- **Title & labels** — the `title`, `labels`, and `emptyCardText` constants
- **Icon** — replace `dragonflyicon.png` (use a square image, ideally 512×512)

After editing, commit and push — the site updates automatically.

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
