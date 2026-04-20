# Sunad P. S. Bhat — Landing page

Static site. Drop the contents of this folder into the root of your GitHub repo.

## Deploy on GitHub Pages (free)

1. Create a new **public** GitHub repo (e.g. `sunad-site`).
2. **Add file → Upload files** → drag in `index.html` and `robots.txt` from this folder.
3. Commit to `main`.
4. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, Folder: `/ (root)` → Save.
5. Wait ~1 minute. Your site is live at `https://<username>.github.io/<repo>/`.

## Privacy / indexing

- `<meta name="robots" content="noindex, nofollow, ...">` is already in `index.html`.
- `robots.txt` tells compliant crawlers to skip everything.
- The URL itself is public. If you need it actually secret (password-gated), use Cloudflare Pages or Netlify instead — ask and I'll write up the steps.

## Contact form

Currently client-side only — it shows a success screen but does not email anyone. To make it deliver to your inbox, use Formspree / Web3Forms (one-line change to the `<form>` tag).
