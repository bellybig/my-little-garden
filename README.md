# My Little Garden

Personal site for **Bryan Johnston** (Product manager). A small, static homepage hosted on [GitHub Pages](https://bellybig.github.io/my-little-garden/).

## What’s here

| File | Purpose |
|------|---------|
| `index.html` | Homepage content (name, bio, links) |
| `assets/styles.css` | Layout, typography, atmospheric background |
| `.nojekyll` | Skip Jekyll so Pages serves the HTML/CSS as-is |

No build step, no theme, no npm/Gemfile.

## Edit the site

1. Open `index.html`.
2. Change the **About** paragraph and any `[Placeholder: …]` copy.
3. Update **Connect** links (`mailto:`, LinkedIn, etc.).
4. Commit and push to the branch GitHub Pages is publishing from (see below).

Styles live in `assets/styles.css` (colors, fonts, spacing).

## Preview locally

From this directory:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Deploy (GitHub Pages)

1. Repo **Settings → Pages**.
2. Source: **Deploy from a branch**.
3. Branch: **`master`** (current default), folder **`/` (root)**.
4. After merge of the personal-site PR, the live URL is:
   **https://bellybig.github.io/my-little-garden/**

### About `master` vs `main`

This repo still uses **`master`** as the default branch (and Pages source). Renaming to `main` is optional: do it in GitHub (**Settings → General → Default branch**), then point Pages at `main`. Until then, keep pushing to `master`.

## License

Personal site content — no separate license declared yet.
